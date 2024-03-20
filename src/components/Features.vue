<script setup lang="ts">
import FeatureCard from "./FeatureCard.vue";

const props = defineProps<{
  features: Array<{ title: string; resume: string }>;
}>();
</script>

<template>
  <div
    ref="featuresRef"
    class="w-full h-full p-20 bg-green-600 grid grid-cols-3 grid-rows-2 gap-10 place-items-center"
  >
    <FeatureCard
      v-for="(feature, index) in props?.features"
      :title="feature.title"
      :resume="feature?.resume"
      :key="index"
    />
  </div>
</template>
