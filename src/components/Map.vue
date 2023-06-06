<template>
  <div id="map" class="h-screen"></div>
</template>

<script setup>
import { onMounted } from 'vue';

onMounted(() => {
  var map = L.map('map').setView([51.505, -0.09], 13);
});
</script>

<style scoped></style>
