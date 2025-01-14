<script setup lang="ts">
import { ref } from 'vue'

//logica app
const saludo = ref('hola edteam')
</script>

<template>
  <!-- html ==> la estructura del componente -->
  <div>
    {{ saludo }}
  </div>
</template>

<style scoped>
/* aqui estara el los estilos
    y el scoped es para que los stilos que se pongo solo funcione en ese componente y si quitamos el scoped los estilos se pondran globalmente */
</style>
