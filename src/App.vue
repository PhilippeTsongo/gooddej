<template>
  <div id="app">
    <RestaurantCard/>
    
  </div>
</template>

<script>
  import RestaurantCard from './components/RestaurantCard.vue'

  export default {
    name: 'App',
    components: {
      RestaurantCard
    }
    
  }
</script>

<style>
  @import url('./style/reset.css');
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    
  }
</style>
