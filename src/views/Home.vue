<template>
  <div class="home">
    <Header />
    <SubHeader />
    <Hero /> 
    <AboutUs />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import SubHeader from '@/components/SubHeader.vue'
import Hero from '@/components/Hero.vue'
import AboutUs from '@/components/AboutUs.vue'
import Footer from '@/components/Footer.vue'
export default {
  name: 'Home',
  components: {
    Header,
    SubHeader,
    Hero,
    AboutUs,
    Footer
  }
}
</script>
