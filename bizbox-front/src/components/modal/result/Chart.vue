<template>
  <div id="app">
    <h1>유동인구</h1>
    <hr />
    <floating-population></floating-population>
    <hr>
    <h1>매출</h1>
    <hr>
    <sales></sales>
  </div>
</template>

<script>
import FloatingPopulation from './Chart/FloatingPopulation.vue'
import Sales from './Chart/Sales.vue'

export default {
  components: {
    FloatingPopulation,
    Sales
  }
}
</script>

<style scoped>
#app {
  display: block;
}
</style>
