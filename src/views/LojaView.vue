<script setup>
import Card from '../components/Card.vue';
module.exports = {
  components: {Card}
}

</script>

<template>
  <main>
    <h1>Loja de camisetas</h1>
    <Card title="Eduardo" description="Futuro programador"></Card>

  </main>
</template>

<style scoped>
  h1 {
    color: red;
    font-size: 40px;
    background-color:yellow;
    padding: 80px;
  }
</style>
