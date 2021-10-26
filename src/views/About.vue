<template>
  <div class="about">
    <About/>
    <Footer class="mt-5"/>
  </div>
</template>

<script>
// @ is an alias to /src
import About from '@/components/About.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    About,
    Footer,
  }
}
</script>

<style scoped>

</style>