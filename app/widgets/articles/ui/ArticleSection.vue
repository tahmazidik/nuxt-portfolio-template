<script setup lang="ts">
import Container from '~/shared/ui/Container.vue'

interface Article {
  id: number
  title: string
  date: string
  image: string
}

const articles: Article[] = [
  {
    id: 1,
    title: 'What is the story behind tattooing',
    date: 'Feb 16, 2021',
    image: '/images/article1.jpg',
  },
  {
    id: 2,
    title: 'Top 10 tatto myths & misconceptions',
    date: 'Feb 17, 2021',
    image: '/images/article2.jpg',
  },
  {
    id: 3,
    title: 'Unbelievable benefits of doing tattoo',
    date: 'Feb 17, 2021',
    image: '/images/article3.jpg',
  },
]
</script>

<template>
  <section id="articles" class="bg-whitepy-20 md:py-24">
    <Container>
      <div class="max-w-6xl mx-auto grid gap-12 md:grid-cols-3 md:gap-16">
        <article
            v-for="article in articles"
            :key="article.id"
            class="flex flex-col"
        >
          <p class="text-[11px] tracking-[0.25em] uppercase text-neutral-500 mb-3">
            Articles:
          </p>

          <div class="overflow-hidden">
            <img
              :src="article.image"
              :alt="article.title"
              class="w-full aspect-[4/3] object-cover transition-transform duration-500 hover:scale-105"
            />
        </div>

          <h3 class="mt-6 text-lg md:text-xl font-medium text-neutral-900">
            {{ article.title }}
          </h3>

          <p class="mt-3 text-sm text-neutral-500">
            {{ article.date }}
          </p>
      </article>
      </div>
    </Container>
  </section>
</template>

<style scoped lang="scss">

</style>