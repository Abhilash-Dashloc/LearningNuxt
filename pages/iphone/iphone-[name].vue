<template>
  <!-- <h2>iphone-{{ $route.params.name }}</h2>  -->
  <div>
    <head>
      <Title>Nuxt 3 iphone {{ name }}</Title>
    </head>
  </div>
  <h2>iphone {{ name }}</h2>
</template>

<script setup>
const route = useRoute();
const name = computed(() => {
  return route.params.name.replaceAll("-", " ");
});
</script>
