<script setup>

</script>
<template>
  <div class="iframe-container">
    <iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=America%2FSao_Paulo&showTabs=1&showPrint=0&hl=pt_BR&src=MmYwMTBjNjUyOTExNDgzZGJmZDQ0MmM3MzIxOTAzMTNmZDQ4YzcyNzcxMTRmNzFkNDIyYzEyNDFiODg0YTcwZkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&color=%238E24AA" 
      style="border:solid 1px #777" 
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
    top:0;
    left:0;
    height: 100%;
    width: 100%;
  }
  iframe{
    width: 100%;
    height: 100%;
  }
</style>
