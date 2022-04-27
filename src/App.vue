<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header>
    <img src="../src/assets/img/logo/ohmyfood.png" alt="logo oh my food" class="header__logo">
    <div class="header__loc">
      <span class="header__loc-map">
        <i class="fas fa-map-marker-alt"></i>
      </span>
      <p class="header__loc-text">Paris, Belleville</p>
    </div>
  </header>
  <footer>
    <img src="../src/assets/img/logo/ohmyfood.png" alt="logo oh my food" class="footer_logo">
  </footer>

  <RouterView />
</template>

<style lang="scss">
header {
  text-align: center;
}

.header__logo {
  padding-top: 15px;
  padding-bottom: 15px;
}
</style>
