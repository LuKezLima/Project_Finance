<template>
<div class="body">
  <div class="nav  w-full h-full shadow-2xl">
      <header class="header w-full h-full shadow-2xl">
          <nav class="flex w-full h-full justify-between items-center">
              <h1 class=" text-3xl ml-8 text-white">Welcome, {{name}}</h1>

              <ul class="flex justify-center items-center gap-9 mr-10">
                  <li class="text-white  underline cursor-pointer" >Home</li>
                  <li class=" text-white underline cursor-pointer">Operations</li>
                  <li class="text-white underline cursor-pointer ">Settings</li>
              </ul>

          </nav>
      </header>

      <div >
          {{content}}
        
      </div>
  </div>
  </div>
</template>

<script>
export default {
    name: 'Base',
    props:["name", "content"],
    data(){
        return{
           
        }
        
    },

    methods: {
        
    },


}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@300;400;500;700&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    color: wheat;
    font-family: 'Ubuntu', sans-serif;
}
.header{
    height: 12%;
    background-color: #2F0F5C;
}


.body{
    background-color: #2F0F5C;
    height: 11vh;
}

.active{
    color: #9598E8 !important;
}

</style>