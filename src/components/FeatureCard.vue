<script setup lang="ts">
import { Images } from "lucide-vue-next";

const props = defineProps<{
  title: string;
  resume: string;
}>();
</script>

<template>
  <div
    class="flex flex-col items-center justify-center h-fit w-fit p-4 space-y-4"
  >
    <Images color="white" :size="36" />
    <h3 class="text-white text-2xl">{{ props?.title }}</h3>
    <p class="text-white text-lg text-center max-w-[400px]">
      {{ props?.resume }}
    </p>
  </div>
</template>
