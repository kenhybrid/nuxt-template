<template>
  <div>
    <div class="container">
      <nuxt />
    </div>
    <BottomNav />
  </div>
</template>

<script>
import BottomNav from '../components/shared/BottomNavbar.vue'
export default {
  components: {
    BottomNav,
  },
}
</script>

<style></style>
