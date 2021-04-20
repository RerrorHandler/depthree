<template>
  <div class="Design">
    <Header />
    <DesignMain />
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
import DesignMain from '@/components/DesignMain.vue'
export default {
    name: 'Design',
  components: {
    Footer,
    Header, 
    DesignMain
  }
}
</script>