<script setup lang="ts">
import Button from "./ui/button/Button.vue";
</script>

<template>
  <div
    class="bg-[url('/src/assets/billboard-background-image.jpg')] bg-center bg h-fit w-full p-40 max-lg:p-10"
  >
    <div class="max-w-2xl space-y-10">
      <h2
        class="text-white text-5xl font-semibold tracking-tight transition-colors first:mt-0 uppercase"
      >
        Take photos like a pro.
      </h2>
      <p class="leading-7 max-w-[500px] text-white">
        With only your Iphone and capture app you can take stunning image like a
        professional Photographer.
      </p>
      <div class="flex flex-row space-x-4 w-full">
        <Button
          class="border-2 border-white rounded-none bg-transparent text-white uppercase hover:bg-white hover:text-black h-14 w-full max-w-[220px] font-bold"
          >Iphone App</Button
        >
        <Button
          class="border-2 border-white rounded-none bg-transparent text-white uppercase hover:bg-green-600 hover:border-green-600 hover:text-white h-14 w-full max-w-[220px] font-bold"
          >Android App</Button
        >
      </div>
    </div>
  </div>
</template>
