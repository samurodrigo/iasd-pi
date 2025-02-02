<template>
  <header>
    <div class="menu-container">
      <div class="homeLink">
        <a href="/">
          <img src="../../assets/img/logo.png" alt="logo" />
          <span>IASD Parada Inglesa</span>
        </a>
      </div>
    </div>
  </header>
</template>

<script setup>

</script>

<style lang="css" scoped>
  header{
    background-color: #043464;
    position:sticky;
    top:0;
  }
  .menu-container{
    display:flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    height: 60px;
    margin: 0 auto;
    padding: 0 20px;
  }

  .menu-container .homeLink a{
    display:flex;
    justify-content: left;
    align-items: center;
    color: white;
    text-decoration: none;
    font-weight: bold;
  }

  .menu-container img{
    max-height: 40px;
    margin-right: 1em;
  }


</style>