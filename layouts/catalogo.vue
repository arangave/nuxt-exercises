<template>
    <div class="catalogo-layout">
      <nav>
        <h2>Menú</h2>
        <div class="nav-buttons">
          <NuxtLink to="/home"><button class="btn-nav">Inicio</button></NuxtLink>
          <NuxtLink to="/catalogo"><button class="btn-nav">Catálogo</button></NuxtLink>
          <NuxtLink to="/productos"><button class="btn-nav">Productos</button></NuxtLink>
          <NuxtLink to="/series-bonitas" class="btn-nav">Series Bonitas</NuxtLink>
        </div>
      </nav>
      <main>
        <NuxtPage />
      </main>
    </div>
  </template>
  
  <style scoped>
 .catalogo-layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

nav {
    background-color: #000000;
    color: aliceblue;
    padding: 1em;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    flex-shrink: 0;
}

.main {
  flex: 1;
  display: flex;
  align-items: center;
  justify-content: center;
}

.nav-buttons {
  display: flex;
  gap: 1em;
  justify-content: center;
  margin-top: 0.5em;
}

.btn-nav {
  background-color: #2ecc71;
  color: white;
  font-size: 1em;
  padding: 0.5em 1em;
  border: none;
  margin-bottom: 1em;
  cursor: pointer;
}

h2 {
  margin: 0;
  font-size: 1.2em;
}
  </style>
  