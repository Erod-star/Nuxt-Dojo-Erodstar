<template>
  <header class="shadow-sm bg-white">
    <nav class="container mx-auto p-4 flex justify-between">
      <NuxtLink to="/" class="font-bold">Nuxt Dojo</NuxtLink>
      <ul class="flex gap-4">
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><NuxtLink to="/products" class="btn">Products</NuxtLink></li>
      </ul>
    </nav>
  </header>

  <!-- Output the page content -->
  <div class="container mx-auto p-4">
    <slot />
  </div>
  <p class="author container mx-auto p-4">
    <strong>Developed by:</strong> Edson Arturo Rodriguez Govea
  </p>
</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
.author {
  font-style: italic;
}
</style>
