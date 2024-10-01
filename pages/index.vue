<script lang="ts" setup>
  import Navbar from '@/components/Navbar.vue';
  import Home from '@/components/Home.vue';
  const About = defineAsyncComponent(() => import('~/components/About.vue'));
  const Services = defineAsyncComponent(() => import('~/components/Services.vue'));
  const Cabang = defineAsyncComponent(() => import('~/components/Cabang.vue'));
  const ViewApk = defineAsyncComponent(() => import('~/components/ViewApk.vue'));
  const Footer = defineAsyncComponent(() => import('~/components/Footer.vue'));
</script>

<template>
  <div class="bg-[#ECECEC] scroll-smooth font-sans">
    <Navbar />
    <Home />
    <About />
    <Services />
    <Cabang />
    <ViewApk />
    <Footer />
  </div>
</template>

<style scoped>
*{
  scroll-behavior: smooth;
}
</style>
