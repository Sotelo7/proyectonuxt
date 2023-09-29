<template>
    <footer class="py-4 text-center text-gray-500 text-sm bg-green-300">
      Carlos Sotelo - {{ currentYear }}
    </footer>
  </template>
  
  <script setup>
  const currentYear = new Date().getUTCFullYear();
  </script>
  
    
  
<style scoped>
footer {
    position: absolute;
    bottom: 0;
    width: 100%;
}
</style>