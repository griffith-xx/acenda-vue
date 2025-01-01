<script setup>
import { Vue3Marquee } from "vue3-marquee";
</script>

<template>
  <section>
    <h1 class="font-bold text-[40px] text-center">OUR PARTNERS</h1>
    <div class="my-[72px]">
      <Vue3Marquee>
        <div class="flex items-center gap-5 text-[#404040] mr-[88px]">
          <img src="../assets/cozybnb.png" alt="cozybnb" />
          <span class="text-2xl">Cozybnb</span>
        </div>
        <div class="flex items-center gap-5 text-[#404040] mr-[88px]">
          <img src="../assets/serendipity.png" alt="serendipity" />
          <span class="text-2xl">Serendipity</span>
        </div>
        <div class="flex items-center gap-5 text-[#404040] mr-[88px]">
          <img src="../assets/hideaway.png" alt="hideaway" />
          <span class="text-2xl">Hideaway</span>
        </div>
        <div class="flex items-center gap-5 text-[#404040] mr-[88px]">
          <img src="../assets/earthly.png" alt="earthly" />
          <span class="text-2xl">Earthly</span>
        </div>
        <div class="flex items-center gap-5 text-[#404040] mr-[88px]">
          <img src="../assets/the-nook.png" alt="The Nook" />
          <span class="text-2xl">The Nook</span>
        </div>
        <div class="flex items-center gap-5 text-[#404040] mr-[88px]">
          <img src="../assets/homely.png" alt="homely" />
          <span class="text-2xl">Homely</span>
        </div>
      </Vue3Marquee>
    </div>
  </section>
</template>
