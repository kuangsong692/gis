<template>
  <div>
    <Navbar />
    <div class="container">
      <div class="chart-left">
        <ChartComponent />
      </div>
      <MapComponent />
      <div class="chart-right">
        <ChartComponent />
      </div>
    </div>
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue';
import MapComponent from './components/MapComponent.vue';
import ChartComponent from './components/ChartComponent.vue';
</script>

<style scoped>
.container {
  display: flex;
  height: 100vh;
}

.chart-left,
.chart-right {
  width: 20%;
  z-index: 999;
}

.chart-left {
  order: 1;
}

.chart-right {
  order: 3;
}

#map {
  order: 2;
  width: 60%;
}
</style>