<template>
    <div>
      <h1>Pagina de Inicio</h1>
      <NuxtLink to="/catalogo">
        <button class="btn-home">Catalogo</button>
      </NuxtLink>
    </div>
  </template>
  
  <style scoped lang="scss">
  h1 {
    color: rgb(25, 79, 97);
  }
  
  .btn-home {
    background-color: #3498db;
    font-size: 1em;
  }
  </style>