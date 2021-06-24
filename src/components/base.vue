<template>
<div class="body w-screen h-screen ">
  <div class="nav  w-full h-screen  shadow-2xl">
      <header class="header w-full shadow-2xl">
          <nav class="flex w-full h-full justify-between items-center">
              <h1 class=" text-3xl ml-8 text-white">Welcome, Levi</h1>

              <ul class="flex justify-center items-center gap-9 mr-10">
                  <li class="text-white  underline active">Home</li>
                  <li class=" text-white underline">Operations</li>
                  <li class="text-white underline ">Settings</li>
              </ul>

          </nav>
      </header>
  </div>
  </div>
</template>

<script>
export default {

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
}

.active{
    color: #9598E8 !important;
}

</style>