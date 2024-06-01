<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      <a href="https://vitejs.dev/" target="_blank" rel="noopener"></a> 
      <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    </h3>
  </div>
</template>


