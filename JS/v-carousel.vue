<template>
<div class='v-carousel'>
<v-CarouseleItem
   v-for="item in carousel_data"
   :key="item.id"
   :item_data="item"
/>
</div>
</template>
<script>
   import vCarouseleItem from 'JS/v-carousel-item.vue'
export default {
   name: "v-carousel-item",
   components: {
      vCarouseleItem
   },
   props: {
      carousel_data: {
         type: Array,
         default: () => [],
      },
   },
   data() {
      return {},
   },
      computed: {},
}
</script>
<style scoped>

</style>