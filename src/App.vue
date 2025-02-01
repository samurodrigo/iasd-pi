<template>
  <div id="app">
    <Header />
    <div class="pages-container">
      <router-view />
    </div>
    <Footer />
  </div>
</template>

<script setup>
  import Header from './components/layout/Header.vue'
  import Footer from './components/layout/Footer.vue'
</script>

<style lang="css" scoped>
  .pages-container {
    max-width: 1200px;
    margin: 0 auto;
    
  }
</style>