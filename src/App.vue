<template>
  <div id="app">
    <RestaurantRow />
     <HomePage />
  </div>
</template>

<script setup>
import RestaurantRow  from './components/RestaurantRow.vue';
import HomePage from './page/homePage.vue'
</script>

<style>
@import url('./style/reset.css');
#app{ 
  padding: 20px;
}

</style>
