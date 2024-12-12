<template>
  <header class="bg-teal-600 text-white py-4">
    <div class="container mx-auto px-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold">Holiday Club</h1>
      <nav class="hidden md:flex">
        <ul class="flex space-x-4">
          <li><nuxt-link to="/">Home</nuxt-link></li>
          <li><a href="#benefits">Benefits</a></li>
          <li><a href="#destinations">Destinations</a></li>
          <li><a href="#testimonials">Testimonials</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>
<style scoped>
header {
  background-color: #008080;
}
nav ul {
  display: flex;
  list-style-type: none;
}
nav ul li {
  margin-right: 15px;
}
</style>
