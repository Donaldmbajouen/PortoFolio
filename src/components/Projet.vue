<template>
<div class="flex flex-col md:flex-row justify-between items-center">
  <h1 class="text-white text-3xl sm:text-4xl md:text-5xl font-bold px-5 mb-8 md:mb-15 text-center md:text-left">Mes Projets Recents</h1>
  <div class="w-full md:w-auto">
    <nav>
      <ul class="flex flex-wrap justify-center md:justify-between items-center text-lg sm:text-xl font-semibold text-white pt-4 md:pt-0">
        <li><a class="p-2 md:p-4 block text-red-500" href="#">Tout</a></li>
        <li><a class="p-2 md:p-4 block hover:text-red-500" href="#">Web</a></li>
        <li><a class="p-2 md:p-4 block hover:text-red-500" href="#">Mobile</a></li>
      </ul>
    </nav>
  </div>
</div>
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6 md:gap-8">
  <Card_V/>
  <Card_V/>
  <Card_V/>
  <Card_V/>
</div>
</template>
<script setup>
import Card_V from './Card_V.vue';
</script>
