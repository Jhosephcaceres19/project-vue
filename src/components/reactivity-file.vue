<script setup lang="ts">
import { ref } from 'vue'

//esto no es un valor reactivo
//que es un valor reactivo es donde se puede editar en un navegador ese valor
const message = 'hola jose estas en el curso de vue'
//este si es un valor reactivo
const message1 = ref('este si es un valor reactivo')
</script>
<template>
  <div>
    {{ message }}
    {{ message1 }}
  </div>
</template>

<style scoped></style>
