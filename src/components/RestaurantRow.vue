 <template>
   <div class="restaurant--row">
      <h2 class="title">
        Nos restaurant
     
      </h2>
      <div class="wrapper--card">
        <RestaurantCard v-for="(card, index) in three_restaurant" 
        :key="index" :info_restaurant="card"/>
    </div>
        
   </div>
 </template>
 
 <script setup>
import RestaurantCard  from './RestaurantCard.vue';


defineProps({
  three_restaurant: Array
})
 
 </script>
 
 <style lang="scss">
    .restaurant--row{
        .wrapper--card{
            display:flex;
            justify-content: space-between;
            align-content: center;
        }
    } 
 </style>