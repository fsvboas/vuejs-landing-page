<script setup lang="ts">
import FeatureCard from "./FeatureCard.vue";

const props = defineProps<{
  features: Array<{ icon: any; title: string; resume: string }>;
}>();
</script>

<template>
  <div
    ref="featuresRef"
    class="w-full h-full p-20 bg-green-600 grid max-sm:grid-cols-1 max-md:grid-cols-2 grid-cols-3 grid-rows-2 gap-10 place-items-center"
  >
    <FeatureCard
      v-for="(feature, index) in props?.features"
      :icon="feature?.icon"
      :title="feature?.title"
      :resume="feature?.resume"
      :key="index"
    />
  </div>
</template>
