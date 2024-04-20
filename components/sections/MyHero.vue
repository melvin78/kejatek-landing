<script setup lang="ts">

import MyHighlightedText from "~/components/reusables/MyHighlightedText.vue";
import MyButton from "~/components/reusables/MyButton.vue";
</script>

<template>
  <section class="text-gray-600 body-font">
    <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
      <div
          class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
        <h1 class="title-font sm:text-6xl text-4xl mb-4 font-medium text-gray-900">
          <MyHighlightedText text="StreamLine"/>
          Your
          <MyHighlightedText text="Rental"/>
          Needs With
          <MyHighlightedText text="Ease"/>
        </h1>
        <p class="mb-8 leading-relaxed">
          <MyHighlightedText text="KejaTek"/>
          , your all-in-one solution for streamlined rental
          management. From tracking paid bills to monitoring late rental payments, our platform empowers landlords with
          real-time insights. Receive instant alerts and notifications for unpaid bills and vacancies, ensuring no
          detail slips through the cracks.
          <MyHighlightedText text="KejaTek"/>
          effortlessly manage your properties and ensure
          seamless tenant interactions
        </p>
        <div class="flex justify-center cursor-pointer">
          <MyButton text="Get Started"/>
        </div>
      </div>
      <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
        <img class="object-cover object-center rounded" alt="hero" src="https://dummyimage.com/720x600">
      </div>
    </div>
  </section>

</template>

<style scoped>

</style>