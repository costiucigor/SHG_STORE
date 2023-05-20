<script setup lang="ts">
import Banner from "./components/Banner.vue";
import Footer from "./components/Footer.vue";

components:{
  Banner;
  Footer
}
</script>

<template>
   <main>
    <Banner />
   </main>
    <Footer />
</template>

<style>
html, body {
  margin: 0;
  background: #000;
}
</style>