<script setup>
const route = useRoute()
</script>

<template>
  <div class="container">
    <h1>Series de: {{ route.params.category }}</h1>
    <NuxtLink :to="`/series-bonitas/${route.params.category}/Espisodio 1 de Spiderman`">
      Spiderman
    </NuxtLink>
  </div>
</template>

<style scoped>
.container {
  text-align: center;
  margin-top: 2em;
}
</style>