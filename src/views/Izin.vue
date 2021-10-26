<template>
  <div class="izin">
    <Permission/>
    <Footer class="mt-5"/>
  </div>
</template>

<script>
import Permission from '@/components/Permission.vue'
import Footer from '@/components/Footer.vue'
export default {
  name: 'Izin',
  components: {
    Permission,
    Footer
  }
}
</script>

<style>

</style>