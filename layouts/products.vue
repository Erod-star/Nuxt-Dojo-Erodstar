<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p-4">
        <NuxtLink to="/products" class="font-bold">Nuxt Dojo Merch</NuxtLink>
      </nav>
    </header>

    <div class="container mx-auto p-4">
      <slot />
    </div>

    <p class="author p-4">
      <strong>Developed by:</strong> Edson Arturo Rodriguez Govea
    </p>

    <footer class="container mx-auto mt-3 p-4 flex justify-between border-t-2">
      <ul class="flex gap-4">
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><NuxtLink to="/products">Products</NuxtLink></li>
      </ul>
    </footer>
  </div>
</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
.author {
  font-style: italic;
  padding: 20px;
}
</style>
