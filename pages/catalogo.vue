<script setup>
definePageMeta({
  layout: 'catalogo'
})
</script>

<template>
  <div class="catalogo-container">
    <h1>Página de Catálogo</h1>
    <NuxtLink to="/home">
      <button class="btn-catalogo">Ir al Inicio</button>
    </NuxtLink>
  </div>
</template>

<style scoped lang="scss">
.catalogo-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 80vh;
  text-align: center;
}

h1 {
  color: rgb(5, 95, 5);
  margin-bottom: 1em;
}

.btn-catalogo {
  background-color: #2ecc71;
  color: white;
  font-size: 1em;
  padding: 0.5em 1em;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  margin-top: 1em;
}
</style>
