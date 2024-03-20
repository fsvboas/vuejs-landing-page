<script setup lang="ts">
import { Camera, Eye, Images, Video } from "lucide-vue-next";
import Button from "./ui/button/Button.vue";
</script>

<template>
  <div class="h-fit w-full flex justify-center items-center space-x-32 py-10">
    <img
      class="select-none"
      src="/src/assets/about-featured-image.png"
      alt="image?.name"
    />

    <div class="w-[550px] space-y-6">
      <h2
        class="text-5xl font-semibold tracking-tight transition-colors first:mt-0 uppercase"
      >
        CAPTURE UNFORGETTABLE MOMENTS.
      </h2>
      <p class="text-lg leading-7">
        Seuismod ligula ipsum vulputate tellus quisque dictum tortor at purus
        faucibus tincidunt, pellentesque habitant morbi tristique senectus et
        netus et malesuada fames ac turpis egestas.
      </p>
      <ul class="space-y-4">
        <li class="flex flex-row items-center space-x-2">
          <Camera />
          <p>Euismod ligula ipsum vulputate tellus.</p>
        </li>
        <li class="flex flex-row items-center space-x-2">
          <Video />
          <p>Morbi non efficitur nibh sit amet est eros.</p>
        </li>
        <li class="flex flex-row items-center space-x-2">
          <Eye />
          <p>Fusce faucibus ante liberonec luctus egestas.</p>
        </li>
        <li class="flex flex-row items-center space-x-2">
          <Images />
          <p>Quisque pretium malesuada ornare.</p>
        </li>
      </ul>
      <div class="flex flex-row space-x-4 w-fit">
        <Button
          class="border-2 border-black rounded-none bg-transparent text-black uppercase hover:bg-black hover:text-white h-14 w-56 font-bold"
          >Watch the video</Button
        >
        <Button variant="link" class="text-black uppercase h-14 w-fit font-bold"
          >get app</Button
        >
      </div>
    </div>
  </div>
</template>
