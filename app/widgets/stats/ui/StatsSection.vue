<script setup lang="ts">
import Container from '~/shared/ui/Container.vue'
</script>

<template>
  <section class="bg-white py-16 min-h-[600px] md:min-h-[680px]">
    <Container>
      <div class="space-y-12">
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
          <div class="flex flex-col items-center text-center">
            <div class="w-28 h-28 rounded-full border border-gray-200 flex items-center justify-center">
              <span class="text-2xl font-semibold">90%</span>
            </div>
            <p class="mt-4 text-[10px] tracking-[0.2em] uppercase text-gray-500">
              Full body tattoo
            </p>
          </div>
          <div class="flex flex-col items-center text-center">
            <div class="w-28 h-28 rounded-full border border-gray-200 flex items-center justify-center">
              <span class="text-2xl font-semibold">80%</span>
            </div>
            <p class="mt-4 text-[10px] tracking-[0.2em] uppercase text-gray-500">
              Safely piercing
            </p>
          </div>
          <div class="flex flex-col items-center text-center">
            <div class="w-28 h-28 rounded-full border border-gray-200 flex items-center justify-center">
              <span class="text-2xl font-semibold">75%</span>
            </div>
            <p class="mt-4 text-[10px] tracking-[0.2em] uppercase text-gray-500">
              Full colour tattoo
            </p>
          </div>

        <div class="flex flex-col items-center text-center">
            <div class="w-28 h-28 rounded-full border border-gray-200 flex items-center justify-center">
              <span class="text-2xl font-semibold">95%</span>
            </div>
            <p class="mt-4 text-[10px] tracking-[0.2em] uppercase text-gray-500">
              Temporary tattoo
            </p>
          </div>
        </div>

        <div class="border-t border-gray-100 pt-15">
          <div class="md:flex md:items-center md:gap-10">
            <div class="text-9xl md:text-7xl text-gray-200 leading-none select-none">
              “
            </div>
            <div class="mt-6 md:mt-0 space-y-4 max-w-3xl">
              <p class="text-sm md:text-base text-gray-700 leading-relaxed">
                The entire team is extremely kind and friendly. They&apos;re
                fantastic. They&apos;re great at what they do! And it&apos;s
                unique. They will properly consult with you.
              </p>

              <div class="flex items-center justify-between text-[11px] uppercase tracking-[0.2em]">
                <span class="text-gray-500">
                  <span class="fon-semibold text-black">Jack Geoffrey</span>
                  <span class="mx-2 text-gray-400">|</span>
                  Tattoo artist
                </span>

                <button class="inline-flex items-center gap-2 text-gray-400 hover:text-black transition">
                  <span class="text-xs">←</span>
                  <span class="text-xs">→</span>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </Container>
  </section>
</template>

<style scoped lang="scss">

</style>