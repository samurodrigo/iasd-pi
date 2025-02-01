<template>
  <div class="footer-wrapper">
    <footer>
      <div class="social-media">
        <a href="https://www.instagram.com/iasd_paradainglesa/" target="_blank">
          <Icon icon="mdi:instagram" height="none" />
        </a>
        <a href="https://www.youtube.com/c/Minist%C3%A9rioJovemParadaInglesa" target="_blank">
          <Icon icon="mdi:youtube" height="none" />
        </a>
      </div>
      <div class="copyright">
        &copy;IASD Parada Inglesa
      </div>
    </footer>
  </div>
</template>

<script>
  import { Icon } from '@iconify/vue2';
  export default {
    components: {
      Icon
    }
  }
</script>

<style lang="css">
  .footer-wrapper{
    color: white;
    background-color:#dae1e8;
    padding: 20px;
    position:absolute;
    bottom:0;
    width: 100%;
    box-sizing: border-box;
    margin-top: auto;
  }

  footer{
    width: 100%;
    display:flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    box-sizing: border-box;
  }

  .copyright{
    text-align: center;
    color: #043464;
    font-weight: bold;
    margin-left: 20px;
  }

  footer svg{
    height: 3em;
    color: #043464;
    margin: 0 10px;
  }




</style>