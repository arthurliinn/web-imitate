<template>
    <body>
      <header>
        <div class="logo">
          <a href="/">
            <img class="logoimg" src="https://official.protaga.jp//images/logo.png"/>
          </a>
        </div>
      </header>
      
      <div class="main">
        <div class="container-1">
          <Slide />
          container01
        </div>
        <div class="container-2">
          container02
        </div>
        <div class="container-3">
          container03
        </div>
        <div class="Iknow">
          I Know
        </div>
        <div class="container-4">
          <section class="section01">
            section01
          </section>
          <section class="section02">
            section02
          </section>
          <section lcass="section03">
            section03
          </section>
        </div>

      </div>


    </body>
</template>



<script>
 import Slide from './Slide.vue'

  export default {
   components: {
    Slide
  }
}


</script>


<style>
  header{
    height:70px;
    background:#fff;
    display:flex;
    position:relative;
  }
  .logo{
    width:160px;
    padding-top:22px;
    margin-left:22px;
  }
  .logoimg{
    max-width:100%;
  }
  




</style>