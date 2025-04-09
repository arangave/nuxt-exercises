
<!--<script setup>
navigateTo('/home') 
</script> -->

<script setup>
onMounted(() => {
  setTimeout(() => {
    navigateTo('/home')
  }, 1000) 
})
</script>

<template>
  <div class="redirect-message">
    <p>Redirigiendo a inicio...</p>
  </div>
</template>

<style scoped>
.redirect-message {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 80vh;
  text-align: center;
  font-size: 1.2em;
  color: #3498db;
}
</style>
