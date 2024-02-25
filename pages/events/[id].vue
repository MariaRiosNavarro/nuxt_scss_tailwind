<script setup>
//how to acces to the params in script
const route = useRoute();
console.log(route.params);

//const nuxt = useNuxtApp()
//console.log(nuxt)
</script>
<template>
  <div>event id: {{ $route.params.id }}</div>
</template>
