<template>
    <div class="layout">
      <nav>
        <h2>Menú</h2>
        <div class="nav-buttons">
          <NuxtLink to="/home"><button class="btn-nav">Inicio</button></NuxtLink>
          <NuxtLink to="/catalogo"><button class="btn-nav">Catálogo</button></NuxtLink>
        </div>
      </nav>
      <main>
        <NuxtPage />
      </main>
      <footer>
        <h2>Footer</h2>
      </footer>
    </div>
  </template>
  
  <style scoped>
.layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

nav, footer {
  background-color: #000000;
  color: aliceblue;
  padding: 1em;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  flex-shrink: 0;
}
footer{
    margin-top: auto; 
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
  background-color: #3498db;
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
  