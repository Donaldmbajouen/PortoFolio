<template>
<div class="flex justify-between">
  <h1 class="text-white text-5xl font-bold px-5 mb-15">Mes Projets Recents</h1>
  <div class="">
    <nav>
      <ul class="md:flex items-center justify-between text-xl font-semibold text-white pt-4 md:pt-0">
        <li><a class="md:p-4 py-3 px-0 block text-red-500" href="#">Tout</a></li>
        <li><a class="md:p-4 py-3 px-0 block hover:text-red-500" href="#">Web</a></li>
        <li><a class="md:p-4 py-3 px-0 block hover:text-red-500" href="#">Mobile</a></li>
      </ul>
    </nav>
  </div>
</div>
<div class="grid grid-cols-3 gap-4">
  <Card_V/>
  <Card_V/>
  <Card_V/>
  <Card_V/>
</div>
</template>
<script setup>
import Card_V from './Card_V.vue';
</script>
