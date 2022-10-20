<script setup>

</script>
<template>
  <div class="iframe-container">
    <iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=America%2FSao_Paulo&mode=WEEK&showPrint=0&showTabs=1&showDate=1&showNav=1&showCalendars=0&showTz=1&title=IASD%20Parada%20Inglesa&src=MmYwMTBjNjUyOTExNDgzZGJmZDQ0MmM3MzIxOTAzMTNmZDQ4YzcyNzcxMTRmNzFkNDIyYzEyNDFiODg0YTcwZkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&color=%238E24AA"
      style="border-width:0" 
      width="800" 
      height="600" 
      frameborder="0" 
      scrolling="no"></iframe>
  </div>
</template>

<style scoped>
  *{
    margin:0;
    padding:0;
  }
  .iframe-container{
    position: absolute;
    padding: 5px;
    top:0;
    left:0;
    height: 100vh;
    width: 100vw;
  }
  iframe{
    width: 100vw;
    height: 100vh;
  }
</style>