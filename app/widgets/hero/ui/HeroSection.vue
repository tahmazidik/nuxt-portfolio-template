<script setup lang="ts">
import Container from '~/shared/ui/Container.vue';
</script>

<template>
  <header class="bg-white">
    <Container>
      <div class="py-4 flex items-center justify-between">
        <div class="flex items-center gap-3">
          <div class="w-10 h-10 rounded-full border border-black flex items-center justify-center text-xs font-semibold">
            VT
          </div>
          <span class="font-semibold tracking-[0.35em] uppercase text-xs">
            The Void Tattoo
          </span>
        </div>

        <nav class="flex items-center gap-6 text-[11px] uppercase">
          <a href="#" class="border-b border-black pb-1">
            Home
          </a>
          <a href="#about" class="text-gray-500 hover:text-black transition">
            About
          </a>
          <a href="#gallery" class="text-gray-500 hover:text-black transition">
            Gallery
          </a>
          <a href="#interview" class="text-gray-500 hover:text-black transition">
            Interview
          </a>
          <a href="#articles" class="text-gray-500 hover:text-black transition">
            Articles
          </a>
          <a href="#contact" class="text-gray-500 hover:text-black transition">
            Contact
          </a>
        </nav>

        <div class="flex items-center gap-3 text-[11px] uppercase text-gray-500">
          <span class="tracking-[0.25em]">Follow</span>
          <span>Fb</span>
          <span>Ig</span>
          <span>Pn</span>
          <span>Tw</span>
        </div>
      </div>
    </Container>
  </header>
  <section class="relative bg-black text-white">
           <img
               src="/images/banner.jpg"
               alt="Tattoo artist making a tattoo"
               class="w-full h-[705px] object-cover"
           />
           <div class="absolute inset-0">
             <Container>
               <div class="flex h-full items-center justify-end">
                 <div class="bg-black/60 p-6 max-w-md text-right space-y-4">
                   <h1 class="text-4xl md:text-5xl font-semibold leading-tight">
                     I'm Void Sir.
                   </h1>

                   <p class="text-sm text-gray-200 leading-relaxed">
                     Tattoos have their own unique power ad magic/ They not only beautify
                     the body but also the psyche.
                   </p>

                   <div>
                     <button class="inline-flex items-center justify-center px-8 py-3 border border-white text-xs tracking-[0.25em] uppercase hover:bg-white hover:text-black transition">
                       Read more
                       <span class="ml-2 text-[10px">→</span>
                     </button>
                   </div>
                 </div>
               </div>
             </Container>
             <div class="absolute bottom-6 left-6 text-white/10 text-6xl md:text-8xl font-bold tracking-[0.25em] uppercase pointer-events-none select-none">
               Tattoo expert
             </div>
           </div>
  </section>
</template>