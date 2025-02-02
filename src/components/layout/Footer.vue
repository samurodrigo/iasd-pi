<template>
  <div class="footer-wrapper">
    <footer>
      <div class="container">
        <div class="logo-footer">
          <img src="../../assets/img/logo-azul.png" alt="logotipo footer" />
          <p>IASD Parada Inglesa</p>
        </div>
      </div>
      <div class="container">
        <h3>Cultos</h3>
        <p>Sábados às 09:30</p>
        <p>Domingos às 19:00</p>
        <p>Quartas às 20:00</p>
      </div>
      <div class="container container-contato">
        <h3>Contato</h3>
        <p><a href="https://maps.app.goo.gl/r4q5Gmp83acSqTDE7" target="_blank"><Icon icon="ic:sharp-location-on" height="none" />Rua Mal. Eurico Gaspar Dutra, 1816</a></p>
        <p>Parada Inglesa - São paulo, SP</p>
        <div class="social-media">
          <a href="https://www.instagram.com/iasd_paradainglesa/" target="_blank">
            <Icon icon="mdi:instagram" height="none" />
          </a>
          <a href="https://www.youtube.com/c/Minist%C3%A9rioJovemParadaInglesa" target="_blank">
            <Icon icon="mdi:youtube" height="none" />
          </a>
        </div>
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
    color: #043464;
    background-color:#dae1e8;
    padding: 20px;
    width: 100%;
    box-sizing: border-box;
    margin-top: auto;
  }

  footer{
    width: 100%;
    display:flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: flex-start;
    max-width: 1200px;
    margin: 0 auto;
    box-sizing: border-box;
    text-align: center;
  }

  .logo-footer
  {
    display:flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
  }
  .logo-footer img{
    max-width: 100px;
  }

  .logo-footer p{
    font-weight: bold;
  }

  .container {
    display:flex;
    flex-direction: column;
    flex-wrap: wrap;
  }

  .container p {
    margin-bottom: 10px;
  }

  .container.full-width{
    width: 100%;
  }

  .social-media{
    display:flex;
    align-items: center;
    justify-content: center;
    flex-direction: row;
    margin-top: 20px;
  }

  footer .container-contato .social-media svg{
    height: 2em;
    color: #043464;
    margin: 0 10px;
  }

  footer h3{
    margin-bottom: 20px;
  }

  footer .container-contato svg {
    height: 1.2em;
    margin: 0;
  }

  footer .container-contato a{
    text-decoration: none;
    color: #043464;
  }

  @media only screen and (max-width: 768px){
    footer {
      flex-direction: column;
      align-items: center;
      justify-content: space-between;
    }

    footer .container{
      margin-bottom: 30px;
    }
  }
</style>