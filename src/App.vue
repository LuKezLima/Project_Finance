<template>
  <div id="app">
    
    <Operations> </Operations>
  

  </div>
</template>

<script>
//  import Login from './components/Login.vue'
import Operations from './components/Operations.vue'


export default {
  name: 'App',
  components: {
    //  Login,
    Operations
  
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@300;400;500;700&display=swap');
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Ubuntu', sans-serif;
}
</style>
