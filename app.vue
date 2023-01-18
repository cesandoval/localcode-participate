<template>
  <NuxtLayout>
    <div class="container">
      <TheHeader />
      <NuxtPage />
      <TheFooter />
    </div>
  </NuxtLayout>
</template>

<script setup>
import TheHeader from '~~/components/TheHeader'
import TheFooter from '~~/components/TheFooter'


</script>

<style>
body {
  font-family: Inter, Helvetica, sans-serif;
  font-size: 1rem;
  line-height: 1.6;
  background: white;
  color: black;
  overflow: hidden;
  font-weight: 400;
}

a {
  color: black;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

a:active,
:focus {
  text-decoration: underline;
  font-weight: 700;
}
.container {
  max-width: 100%;
  min-height: 99vh;
  margin: 0 2rem 0 2rem;
  background: white;
  flex-direction: column;
  border: 1px solid red;
}

h1 {
  font-weight: 900;
}

h2 {
  font-weight: 400;
}

h3 {
  font-weight: 400;
}

h4 {
  font-weight: 400;
}
</style>
