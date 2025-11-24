<script setup lang="ts">
import {RectangleIcon} from '~/sharded/icons';
import {ArrowIcon} from '~/sharded/icons';
import {Image} from '~/sharded/icons';
</script>

<template>
  <div
      class="flex flex-col items-center justify-between min-h-screen text-center bg-[#121011] px-[22px] py-[24px] relative">
    <div class="flex gap-2 cursor-default">
      <img :src="RectangleIcon" alt="RectangleIcon"/>
      <p class="font-mono text-[14px] sm:text-[18px] font-normal leading-[0.8] tracking-[-0.5px] text-[#F6F6F6] cursor-default">
        COMING SOON</p>
      <img :src="RectangleIcon" alt="RectangleIcon"/>
    </div>

    <div
        class="hidden sm:flex items-center justify-between w-full text-[#F6F6F6] font-normal leading-[0.8] tracking-[-0.5px]">
      <NuxtLink
          to="https://dprofile.ru/idubovcev"
          target="_blank"
          rel="noopener noreferrer"
          class="font-mono text-[18px]cursor-pointer"
      >
        DPROFILE
      </NuxtLink>
      <h1 class="font-[Panama] text-[160px] tracking-[-12px] cursor-default">
        DUB<br/>
        DIGITAL
      </h1>
      <NuxtLink
          to="https://t.me/idubovcev"
          target="_blank"
          rel="noopener noreferrer"
          class="font-mono text-[18px] cursor-pointer"
      >
        TELEGRAM
      </NuxtLink>
    </div>

    <div class="flex flex-col w-full text-[#F6F6F6] font-normal leading-[0.8] tracking-[-0.5px] sm:hidden">
      <div class="flex flex-col gap-2">
        <NuxtLink
            to="https://dprofile.ru/idubovcev"
            target="_blank"
            rel="noopener noreferrer"
            class="font-mono text-[14px] cursor-pointer"
        >
          DPROFILE
        </NuxtLink>
        <NuxtLink
            to="https://t.me/idubovcev"
            target="_blank"
            rel="noopener noreferrer"
            class="font-mono text-[14px] cursor-pointer"
        >
          TELEGRAM
        </NuxtLink>
      </div>
      <h1 class="font-[Panama] text-[80px] tracking-[-6px] cursor-default">
        DUB<br/>
        DIGITAL
      </h1>
    </div>

    <div class="hidden sm:block font-mono text-[#F6F6F6] font-normal text-[18px] leading-[0.8] tracking-[-0.5px]">
      <p class="cursor-default">
        YOUR DIGITAL PARTNER FOR SUCCESS
      </p>

      <div class="absolute bottom-[24px] right-[22px]">
        <NuxtLink
            to="https://dprofile.ru/idubovcev"
            target="_blank"
            rel="noopener noreferrer"
        >
          <div class="flex flex-col items-center gap-2">
            <img :src="Image" alt="Profile" class="object-contain"/>
            <div class="flex items-center justify-between w-full gap-[10px]">
              <img :src="ArrowIcon" alt="ArrowIcon" class="w-[19px] h-[14px]"/>
              <p class="cursor-default">RECENT WORK</p>
            </div>
          </div>
        </NuxtLink>
      </div>
    </div>

    <div class="block font-mono text-[#F6F6F6] font-normal text-[14px] leading-[0.8] tracking-[-0.5px] sm:hidden">
      <div class="flex flex-col">
        <NuxtLink
            to="https://dprofile.ru/idubovcev"
            target="_blank"
            rel="noopener noreferrer"
        >
          <div class="flex flex-col items-center gap-2">
            <img :src="Image" alt="Profile" class="object-contain w-[200px] h-[120px]"/>
            <div class="flex items-center justify-between w-full gap-[10px]">
              <img :src="ArrowIcon" alt="ArrowIcon" class="w-[15px] h-[11px]"/>
              <p>RECENT WORK</p>
            </div>
          </div>
        </NuxtLink>
      </div>
      <p>
        YOUR DIGITAL PARTNER FOR SUCCESS
      </p>
    </div>
  </div>
</template>