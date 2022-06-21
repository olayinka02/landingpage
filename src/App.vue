<template>
  <div id="app">
    <NavbarPage />
    <HeroSection />
    <HowWork />
    <FeaturesPage />
    <TestimonialPage />
    <NewsLetter />
    <BottomNav />
  </div>
</template>

<script>
import NavbarPage from './components/homepage/NavbarPage.vue'
import HeroSection from './components/homepage/HeroSection.vue'
import HowWork from './components/homepage/HowWork.vue'
import FeaturesPage from './components/homepage/FeaturesPage.vue'
import TestimonialPage from './components/homepage/TestimonialPage.vue'
import NewsLetter from './components/homepage/NewsLetter.vue'
import BottomNav from './components/homepage/BottomNav.vue'



export default {
  name: 'App',
  components: {
    NavbarPage,
    HeroSection,
    HowWork,
    FeaturesPage,
    TestimonialPage,
    NewsLetter,
    BottomNav
}
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@200;400&display=swap');

#app {
 font-family: 'Nunito', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 0;
}
</style>
