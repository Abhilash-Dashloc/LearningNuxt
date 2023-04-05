import { NuxtLink } from '~/.nuxt/components';

<template>
  <div>
    <Head>
      <Title>Home</Title>
    </Head>
  </div>
  <div>Home Page</div>

  <button @click="movetoAbout">Take me to About Page</button>
</template>

<script setup>
const movetoAbout = () => {
  navigateTo("about");
};
</script>
