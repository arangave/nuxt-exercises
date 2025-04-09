<script setup>
const route = useRoute()
</script>

<template>
  <div class="container">
    <h1>Categoría: {{ route.params.category }}</h1>
    <h2>Titulo: {{ route.params.title }}</h2>
  </div>
</template>

<style scoped>
.container {
  text-align: center;
  margin-top: 2em;
}
</style>