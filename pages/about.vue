<template>
  <div class="about">
    <h2>This is the about.</h2>
    <NuxtPage />
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Local Code - About',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Local Code Lab, Drawing Together',
        },
      ],
    }
  },
}
</script>

<style>
.about {
  height: 82.75vh;
}
</style>
