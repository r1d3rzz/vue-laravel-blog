<template>
  <div class="blogs">
    <Navbar />
    <Hero />
    <BlogsSection />
    <Footer />
  </div>
</template>

<script>
import BlogsSection from "./BlogsSection.vue";
import Footer from "./Footer.vue";
import Hero from "./Hero.vue";
import Navbar from "./Navbar.vue";
export default {
  components: { Hero, Navbar, Footer, BlogsSection },
};
</script>

<style>
</style>
