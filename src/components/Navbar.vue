<script setup lang="ts">
import { Facebook, Instagram, Twitter } from "lucide-vue-next";
</script>

<template>
  <nav
    class="flex flex-row bg-green-600 h-20 w-full items-center px-40 justify-between"
  >
    <ul class="flex flex-row space-x-4">
      <li><a href="/" class="text-white hover:underline">Home</a></li>
      <li>
        <a href="#features" class="text-white hover:underline">Features</a>
      </li>
      <li>
        <a href="#testimonials" class="text-white hover:underline"
          >Testimonials</a
        >
      </li>
    </ul>
    <ul class="flex flex-row space-x-4">
      <li class="bg-white h-8 w-8 rounded-full group">
        <a
          href="/"
          class="w-full h-full rounded-full outline-none flex justify-center items-center"
        >
          <Twitter
            :size="18"
            class="fill-green-600 text-transparent transition-all duration-150 group-hover:-translate-y-1"
          />
        </a>
      </li>
      <li class="bg-white h-8 w-8 rounded-full group">
        <a
          href="/"
          class="w-full h-full rounded-full outline-none flex justify-center items-center"
        >
          <Instagram
            :size="18"
            class="text-green-600 transition-all duration-150 group-hover:-translate-y-1"
          />
        </a>
      </li>
      <li class="bg-white h-8 w-8 rounded-full group">
        <a
          href="/"
          class="w-full h-full rounded-full outline-none flex justify-center items-center"
        >
          <Facebook
            :size="18"
            class="fill-green-600 text-transparent transition-all duration-150 group-hover:-translate-y-1"
          />
        </a>
      </li>
    </ul>
  </nav>
</template>
