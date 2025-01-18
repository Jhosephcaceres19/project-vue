<script setup lang="ts">
import { ref } from 'vue'

const text = ref<string>('hola edteam')
const isVisible = ref<boolean>(true)
const age = ref<number>(20)
</script>
<template>
  <div v-if="isVisible">
    {{ text }}
  </div>
  <div v-else-if="age > 18">Hola es mayor de edad</div>
  <div v-else>
    <span>texto alternativo</span>
  </div>
</template>

<style scoped></style>
