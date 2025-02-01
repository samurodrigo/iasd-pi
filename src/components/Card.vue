<template>
  <div>
  <h1>{{ title }}</h1>
  <div>{{ description }}</div>
</div>
</template>

<script setup>
  module.exports =  {
    props: ['title', 'description']
  }
</script>

<style scoped>
</style>