<!-- eslint-disable prettier/prettier -->

<template>
  <div class="Map-App">
    <div id="map"></div>
    <NuxtPage />
  </div>
</template>

<script setup>
import mapboxgl from 'mapbox-gl'

mapboxgl.accessToken =
  'pk.eyJ1IjoiY3pob25nIiwiYSI6ImNsZDBscHQ5bjJ5Y3gzb214YWswOXA4cmsifQ.rJcTyduLTZF0vCuYzOT08Q'

console.log('making map1')

const AIR_PORTS =
  'https://d2ad6b4ur7yvpq.cloudfront.net/naturalearth-3.3.0/ne_10m_airports.geojson'

console.log('making map2')

const map = new mapboxgl.Map({
  container: 'map',
  style:
    'https://basemaps.cartocdn.com/gl/positron-nolabels-gl-style/style.json',
  center: [0.45, 51.47],
  zoom: 4,
  bearing: 0,
  pitch: 30,
})
</script>

<style>
.Map-App {
  height: 82.75vh;
  margin: 0;
  padding: 0;
}

#map {
  position: relative;
}
</style>
