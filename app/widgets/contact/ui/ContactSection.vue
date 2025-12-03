<script setup lang="ts">
import Container from '~/shared/ui/Container.vue'

const offices = [
  {
    id: 'la',
    title: 'LA OFFICE',
    description:
        'In velit arcu posuere integer sit amet, consectetur nun adipiscing elit. Duis porttitor massa tellus',
    address: '784 Norman Street, Los Angeles',
    phone: '+49 93 30493943',
    email: 'contact@templatesjungle.com',
  },
  {
    id: 'nyc',
    title: 'NYC OFFICE',
    description:
        'Sit amet, consectetur nun in velit arcu posuere integer. Adipiscing elit duis porttitor massa tellus',
    address: '1630 Elm Drive, New York City',
    phone: '+49 34 36573355',
    email: 'contact@templatesjungle.com',
  },
]
</script>

<template>
  <section id="contact" class="bg-[#f9f9f9] py-[180px]">
    <Container>
      <div class="grid gap-16 lg:grid-cols-[minmax(0,1.2fr)_minmax(0,1fr)]">
        <div class="space-y-16">
          <h2 class="text-4xl md:text-5xl font-semibold leading-tight">
            <span class="block">GET IN TOUCH</span>
            <span class="block">WITH ME:</span>
          </h2>

          <div class="grid gap-10 md:grid-cols-2">
            <article
              v-for="office in offices"
              :key="office.id"
              class="space-y-3 text-sm text-neutral-700">
              <p class="text-xs font-bold tracking-[0.25em] uppercase text-neutral-700">
                {{ office.title }}
              </p>

              <p class="leading-relaxed">
                {{ office.description }}
              </p>

              <ul class="space-y-2 text-sm">
                <li class="flex items-center gap-2">
                  <span class="text-base">📍</span>
                  <p>{{ office.address }}</p>
                </li>
                <li class="flex items-center gap-2">
                  <span class="text-base">📞</span>
                  <p>{{ office.phone }}</p>
                </li>
                <li class="flex items-center gap-2">
                  <span class="text-base">✉</span>
                  <span>{{ office.email }}</span>
                </li>
              </ul>
            </article>
          </div>
        </div>

        <div>
          <form class="space-y-8 py-[130px]" @submit.prevent>
            <div>
              <input
                type="text"
                placeholder="write your name here"
                class="w-full border-b border-neutral-300 py-3 text-sm bg-transparent
                      placeholder:text-neutral-400 focus:outline-none focus:border-black"
              />
            </div>

            <div>
              <input
                type="text"
                placeholder="write your email here"
                class="w-full border-b border-neutral-300 py-3 text-sm bg-transparent
                placeholder:text-neutral-400 focus:outline-none focus:border-black"
              />
            </div>

            <div>
              <input
                type="text"
                placeholder="Write your message here"
                class="w-full border-b border-neutral-300 py-3 text-sm bg-transparent
                    placeholder:text-neutral-400 focus:outline-none focus:border-black"
              />
            </div>

            <button
              type="submit"
              class="inline-flex items-center justify-center px-4 py-4 text-xs font-semibold
                    tracking-[0.25em] uppercase bg-black text-white hover:bg-neutral-900
                      transition-colors">
              SEND IT
            </button>
          </form>
        </div>
      </div>
    </Container>
  </section>
</template>

<style scoped lang="scss">

</style>