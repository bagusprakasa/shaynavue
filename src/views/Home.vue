<template>
  <div class="home">
    <Header />
    <Hero />
    <Banner />
    <Insta />
    <Logo />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Hero from "@/components/Hero.vue";
import Banner from "@/components/Banner.vue";
import Insta from "@/components/Instagram.vue";
import Logo from "@/components/Partner.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Hero,
    Banner,
    Insta,
    Logo,
    Footer,
  },
};
</script>