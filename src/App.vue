<template>
  <div id="app">
    <Base> </Base>
    <!-- <Login>  </Login> -->
  

  </div>
</template>

<script>
// import Login from './components/Login.vue'
import Base from './components/base.vue'


export default {
  name: 'App',
  components: {
    // Login,
    Base,
  
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
