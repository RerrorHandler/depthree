<template>
    <div class="wrapper">
        <Header />
        <PriceMain />
        <Footer />
    </div>
</template>
<style>
.wrapper {
    font-family: "PALA";
}
</style>


<script>
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
import PriceMain from '@/components/PriceMain.vue'
export default {
    name: 'Home',
  components: {
    Footer,
    Header,
    PriceMain 
  }
}
</script>
