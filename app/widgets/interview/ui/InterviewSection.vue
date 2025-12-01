<script setup lang="ts">
import Container from '~/shared/ui/Container.vue'
</script>

<template>
  <section id="interview" class="bg-black">
    <div class="relative">
      <img
          src="/images/banner-2.jpg"
          alt="Tattoo artist in studio"
          class="w-full h-[700px] md:h-[900px] object-cover opacity-80"
      />

      <div class="absolute inset-0 bg-black/30">
        <Container>
          <div class="flex h-full items-center pt-[250px] md:pt-[300px]">
            <div class="max-w-3xl space-y-6 text-white">
              <p class="text-3xl md:text-4xl lg:text-5xl font-semibold leading-tight">
                “Consider What You Desire.<br />
                Your Tattoo Artist Will Never<br />
                Tell You What Tattoo To Have.”
              </p>

              <div class="mt-8">
                <button class="inline-flex items-center gap-4 group">
                  <span class="flex h-16 w-16 items-center justify-center rounded-full bg-white text-black border border-white">
                     <span class="ml-1 border-l-[10px] border-l-current border-y-[6px] border-y-transparent"/>
                  </span>

                  <span class="text-xs md:text-sm tracking-[0.25em] uppercase">
                    Watch it now
                  </span>
                </button>
              </div>
            </div>
          </div>
        </Container>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">

</style>