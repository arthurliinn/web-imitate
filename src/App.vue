<template>
  <div id="app">
    <mainPage />
    <h1>hello</h1>     
  </div>
  
</template>

<script>


import mainPage from './components/mainPage.vue'

export default {
  name: 'app',
  components: {
    mainPage
    
    
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  
}

body{
  margin:0;
  padding:0;
}
</style>
