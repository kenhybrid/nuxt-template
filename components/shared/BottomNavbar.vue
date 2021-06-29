<template>
  <nav class="nav hide-sm hide-md hide-lg">
    <nuxt-link to="/" class="nav__link">
      <i class="material-icons nav__icon">home</i>
      <span class="nav__text">Home</span>
    </nuxt-link>
    <nuxt-link to="/about" class="nav__link nav__link--active">
      <i class="material-icons nav__icon">person</i>
      <span class="nav__text">Profile</span>
    </nuxt-link>
    <!-- <a href="#" class="nav__link">
      <i class="material-icons nav__icon">devices</i>
      <span class="nav__text">Devices</span>
    </a> -->
    <!-- <a href="#" class="nav__link">
      <i class="material-icons nav__icon">lock</i>
      <span class="nav__text">Privacy</span>
    </a> -->
    <nuxt-link to="/login" class="nav__link">
      <i class="material-icons nav__icon">settings</i>
      <span class="nav__text">Settings</span>
    </nuxt-link>
  </nav>
</template>

<script>
export default {};
</script>

<style>

</style>
