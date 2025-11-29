<script setup lang="ts">
import Container from '~/shared/ui/Container.vue'
</script>

<template>
  <section class="bg-[#f9f9f9] py-16">
    <Container>
      <div class="space-y-8">
        <h2 class="text-sm md:text-xl font-semibold tracking-[0.25em] uppercase text-black">
          Check my<br />
          gallery:
        </h2>

        <div class="grid grid-cols-2 md:grid-cols-4 gap-x-4 gap-y-2 md:auto-rows-[180px] md:grid-flow-dense">
          <div class="overflow-hidden md:row-span-1 group">
            <img
                src="/images/1.jpg"
                alt="Tattoo artwork 1"
                class="w-full h-full object-cover transition-transform duration-300 ease-out group-hover:scale-105 cursor-zoom-in"
            />
          </div>
          <div class="overflow-hidden md:row-span-2 group">
            <img
                src="/images/2.jpg"
                alt="Tattoo artwork 2"
                class="w-full h-full object-cover transition-transform duration-300 ease-out group-hover:scale-105 cursor-zoom-in"
            />
          </div>
          <div class="overflow-hidden md:row-span-1 group">
            <img
                src="/images/3.jpg"
                alt="Tattoo artwork 3"
                class="w-full h-full object-cover transition-transform duration-300 ease-out group-hover:scale-105 cursor-zoom-in"
            />
          </div>
          <div class="overflow-hidden md:row-span-2 group">
            <img
                src="/images/4.jpg"
                alt="Tattoo artwork 4"
                class="w-full h-full object-cover transition-transform duration-300 ease-out group-hover:scale-105 cursor-zoom-in"
            />
          </div>
          <div class="overflow-hidden md:row-span-2 group">
            <img
                src="/images/5.jpg"
                alt="Tattoo artwork 5"
                class="w-full h-full object-cover transition-transform duration-300 ease-out group-hover:scale-105 cursor-zoom-in"
            />
          </div>
          <div class="overflow-hidden md:row-span-2 group">
            <img
                src="/images/7.jpg"
                alt="Tattoo artwork 7"
                class="w-full h-full object-cover transition-transform duration-300 ease-out group-hover:scale-105 cursor-zoom-in"
            />
          </div>
          <div class="overflow-hidden md:row-span-1 group">
            <img
                src="/images/8.jpg"
                alt="Tattoo artwork 8"
                class="w-full h-full object-cover transition-transform duration-300 ease-out group-hover:scale-105 cursor-zoom-in"
            />
          </div>

          <div class="overflow-hidden md:row-span-1 group">
            <img
                src="/images/6.jpg"
                alt="Tattoo artwork 6"
                class="w-full h-full object-cover transition-transform duration-300 ease-out group-hover:scale-105 cursor-zoom-in"
            />
          </div>
        </div>

        <div class="mt-8 flex justify-center">
          <button class="inline-flex items-center px-6 py-3 text-xs md:text-sm tracking-[0.25em] uppercase border border-black text-gray-800 hover:bg-black hover:text-white transition">
            View full gallery
            <span class="ml-2 text-[10px]">→</span>
          </button>
        </div>
        </div>
    </Container>
  </section>
</template>

<style scoped lang="scss">

</style>

