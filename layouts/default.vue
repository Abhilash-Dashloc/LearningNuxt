<template>
  <div>
    <p>Default layout appears on all pages</p>
    <nav
      class="bg-purple-700 text-white text-lg flex justify-around shadow-lg p-3"
    >
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/about">About</NuxtLink>
      <NuxtLink to="/iphone">Iphones</NuxtLink>
      <NuxtLink to="/Profile">Profile</NuxtLink>
    </nav>
    <!-- slot will use page content -->
    <slot />
  </div>
</template>
