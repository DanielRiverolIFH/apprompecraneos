<template>
  <div id="app">
    <!-- Barra navegacion -->
    <Navbar/>
   <div class="row">
     <div class="col m-3"> <img class="img-fluid" alt="NYSL" src="./assets/logo.png"></div>
   </div>
   <div class="container">
    <div class="row">
      <div class="col">
        <Schedules/>
      </div>
     </div>
   </div>
  </div>
</template>

<script>

import Navbar from '@/components/Navbar.vue'
import Schedules from '@/components/Schedules.vue'

export default {
  name: 'app',
  components: {
    Navbar,
    Schedules
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
