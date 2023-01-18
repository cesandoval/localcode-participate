<template>
  <header class="header">
    <h1 class="title">Local Code Lab</h1>
    <h2 class="right">
      <nuxt-link to="/siteselection">Select</nuxt-link> >
      <nuxt-link to="/about">Design</nuxt-link> >
      <nuxt-link to="/">Maintain</nuxt-link>
    </h2>
  </header>
</template>

<script setup>
</script>




<style>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-top: 2px solid black;
  border-bottom: 2px solid black;
  margin:0;
}
</style>
