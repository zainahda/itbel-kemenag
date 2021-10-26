<template>
  <div class="home">
    <Jumbotron/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Jumbotron from '@/components/Jumbotron.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Jumbotron,
    Footer
  }
}
</script>

<style scoped>

</style>