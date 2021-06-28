<template>

<div class="operations w-screen h-screen">
<Base2>
 </Base2>

 <main class="main   w-5/6 bg-gray-200 flex justify-center items-center flex-col">


  <div class=" bg-gray-400 w-full  h-1/6">
    <h1>Operations</h1>   
  </div>
  <div class="table  bg-gray-300 w-full h-5/6">
    <h1>table</h1>
  </div>
   
 </main>


  </div>
</template>

<script>

import Base2 from './base2.vue'

export default {
 name: 'operations',
  components: {
    Base2,
  
  }
}
</script>

<style>
*{
    margin:  0;
    padding: 0;
    box-sizing: border-box;
    color: rgb(0, 0, 0);
}

.operations{
  background-color: tomato;
}


.main{
  margin: 0 auto;
  height: 89vh
}
</style>