<template>
  <div class="home-container">
    <h1>Página de Inicio</h1>
    <NuxtLink to="/catalogo">
      <button class="btn-home">Ver Catálogo</button>
    </NuxtLink>
  </div>
</template>

<style scoped lang="scss">
.home-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 80vh;
  text-align: center;
}

h1 {
  color: rgb(25, 79, 97);
  margin-bottom: 1em;
}

.btn-home {
  background-color: #3498db;
  color: white;
  font-size: 1em;
  padding: 0.5em 1em;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  margin-top: 1em;
}
</style>

