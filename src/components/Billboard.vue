<script setup lang="ts">
import Button from "./ui/button/Button.vue";
</script>

<template>
  <div
    class="bg-[url('/src/assets/billboard-background-image.jpg')] bg-center bg h-fit w-full py-40 px-40"
  >
    <div class="max-w-2xl space-y-10">
      <h2
        class="scroll-m-20 text-5xl font-semibold tracking-tight transition-colors first:mt-0 uppercase"
      >
        Take photos like a pro.
      </h2>
      <p class="leading-7 w-[500px]">
        With only your Iphone and capture app you can take stunning image like a
        professional Photographer.
      </p>
      <div class="flex flex-row space-x-4 w-fit">
        <Button
          class="border-2 border-black rounded-none bg-transparent text-black uppercase hover:bg-black hover:text-white h-14 w-56 font-bold"
          >Iphone App</Button
        >
        <Button
          class="border-2 border-black rounded-none bg-transparent text-black uppercase hover:bg-green-600 hover:border-green-600 hover:text-white h-14 w-56 font-bold"
          >Android App</Button
        >
      </div>
    </div>
  </div>
</template>
