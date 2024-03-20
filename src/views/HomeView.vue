<script setup lang="ts">
import About from "@/components/About.vue";
import Billboard from "@/components/Billboard.vue";
import Features from "@/components/Features.vue";
import Footer from "@/components/Footer.vue";
import Marquee from "@/components/Marquee.vue";
import Navbar from "@/components/Navbar.vue";
const sponsors = [
  {
    name: "Google",
    imageUrl: "/src/assets/sponsors/google.png",
  },
  {
    name: "Facebook",
    imageUrl: "/src/assets/sponsors/facebook.png",
  },
  {
    name: "Yahoo",
    imageUrl: "/src/assets/sponsors/yahoo.png",
  },
  {
    name: "PayPal",
    imageUrl: "/src/assets/sponsors/paypal.png",
  },
];

const features = [
  {
    title: "MALESUADA FAMES TURPIS.",
    resume:
      "vel ultrices mauris libero id diam. Vivamus tellus sagittis facilisis nisi quis mollis risus quisque ultrices elit.",
  },
  {
    title: "MALESUADA FAMES TURPIS.",
    resume:
      "vel ultrices mauris libero id diam. Vivamus tellus sagittis facilisis nisi quis mollis risus quisque ultrices elit.",
  },
  {
    title: "MALESUADA FAMES TURPIS.",
    resume:
      "vel ultrices mauris libero id diam. Vivamus tellus sagittis facilisis nisi quis mollis risus quisque ultrices elit.",
  },
  {
    title: "MALESUADA FAMES TURPIS.",
    resume:
      "vel ultrices mauris libero id diam. Vivamus tellus sagittis facilisis nisi quis mollis risus quisque ultrices elit.",
  },
  {
    title: "MALESUADA FAMES TURPIS.",
    resume:
      "vel ultrices mauris libero id diam. Vivamus tellus sagittis facilisis nisi quis mollis risus quisque ultrices elit.",
  },
  {
    title: "MALESUADA FAMES TURPIS.",
    resume:
      "vel ultrices mauris libero id diam. Vivamus tellus sagittis facilisis nisi quis mollis risus quisque ultrices elit.",
  },
];
</script>

<template>
  <Navbar />
  <Billboard />
  <Marquee :images="sponsors" />
  <About />
  <Features :features="features" />
  <Footer />
</template>
