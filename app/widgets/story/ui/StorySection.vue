<script setup lang="ts">
import Container from '~/shared/ui/Container.vue'
</script>

<template>
  <section class="bg-white py-28 min-h-[600px] md:min-h-[680px]">
    <Container>
      <div class="grid gap-8 md:grid-cols-[minmax(0,260px)_minmax(0,1fr)] items-center">
          <div class="flex flex-col items-center md:items-start gap-6">
            <span class="text-[220px] md:text-[280px] leading-none font-semibold text-black">
              01
            </span>
<!--            <span-->
<!--                class="inline-block text-[140px] md:text-[200px] leading-none font-semibold-->
<!--         text-transparent bg-clip-text bg-center bg-cover bg-no-repeat-->
<!--         bg-[url('/images/story-01.jpg')]"-->
<!--            >-->
<!--  01-->
<!--</span>-->

          </div>
        <div class="max-w-xl">
          <h2 class="text-xl md:text-2xl font-semibold tracking-[0.25em] uppercase text-black">
            My story:
          </h2>
          <p class="mt-6 text-sm text-gray-700 leading-relaxed">
            In velit quo possimus impedit. Dolor sit amet, consectetur non adipisicing elit.
            Duis nostrum maiores id illo, sed sed sequi magni quasi beatae tenetur?
          </p>

          <button class="mt-6 inline-flex items-center text-[11px] tracking-[0.25em] uppercase
           text-gray-700 hover:text-black transition">
            Read more
            <span class="ml-2 text-[10px]">→</span>
          </button>
        </div>
      </div>
    </Container>
  </section>
</template>

<style scoped lang="scss">

</style>