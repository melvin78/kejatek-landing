<script setup lang="ts">

import MyHighlightedText from "~/components/reusables/MyHighlightedText.vue";
import MyFeatures from "~/components/sections/MyFeatures.vue";
</script>

<template>
  <section class="text-gray-600 body-font">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-col text-center w-full mb-20">
        <h1 class="sm:text-3xl text-2xl font-medium title-font mb-4 text-gray-900"><MyHighlightedText text="KejaTek Rental Management System"/></h1>
        <p class="lg:w-2/3 mx-auto leading-relaxed text-base">        <MyHighlightedText text="KejaTek"/>
          , your all-in-one solution for streamlined rental
          management. From tracking paid bills to monitoring late rental payments, our platform empowers landlords with
          real-time insights. Receive instant alerts and notifications for unpaid bills and vacancies, ensuring no
          detail slips through the cracks.
          <MyHighlightedText text="KejaTek"/>
          effortlessly manage your properties and ensure
          seamless tenant interactions. Explore some of the <MyHighlightedText text="features"/> below.</p>
      </div>
    </div>
  </section>
  <MyFeatures/>
</template>

<style scoped>

</style>