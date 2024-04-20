<script setup lang="ts">

import MyHeader from "~/components/sections/MyHeader.vue";
import MyHero from "~/components/sections/MyHero.vue";
import MainSection from "~/components/sections/MainSection.vue";
import MyFooter from "~/components/sections/MyFooter.vue";
import MySplash from "~/components/sections/MySplash.vue";
</script>

<template>
  <MyHeader/>
  <div class="mx-auto px-4 sm:px-6 lg:px-8 max-w-7xl gap-16 sm:gap-y-24 flex flex-col">
    <MyHero/>
    <MainSection/>
    <MyFooter/>
  </div>

</template>

<style scoped>

</style>