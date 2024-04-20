<script setup lang="ts">

import MyHighlightedText from "~/components/reusables/MyHighlightedText.vue";
import MyFeatures from "~/components/sections/MyFeatures.vue";
</script>

<template>
  <section class="text-gray-600 body-font">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-col text-center w-full mb-20">
        <h1 class="sm:text-3xl text-2xl font-medium title-font mb-4 text-gray-900"><MyHighlightedText text="KejaTek Rental Management System"/></h1>
        <p class="lg:w-2/3 mx-auto leading-relaxed text-base">KejaTek offers a one stop solution to manage all your properties. If you need to keep track of all your tenants
        rental payments, fees and expenses. Some of the features are outlined below</p>
      </div>
    </div>
  </section>
  <MyFeatures/>
</template>

<style scoped>

</style>