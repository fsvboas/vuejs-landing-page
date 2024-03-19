<script lang="ts">
export default {
  props: {
    images: {
      type: Array<{ name: string; imageUrl: string }>,
      required: true,
    },
  },
};
</script>

<template>
  <Vue3Marquee>
    <img
      class="select-none"
      v-for="(image, index) in images"
      :src="image?.imageUrl"
      :alt="image?.name"
      :key="index"
    />
  </Vue3Marquee>
</template>
