<template>
<div class="flex flex-col md:flex-row w-full mx-auto text-white">
  <div class="w-full md:w-[50%] px-5 mb-10 md:mb-0">
    <h1 class="text-white text-3xl md:text-5xl font-bold mb-15 text-center md:text-left">Parcours Academique</h1>
      <Card_H class="w-full max-w-[500px] mx-auto md:mx-0"/>
      <Card_H class="w-full max-w-[500px] mx-auto md:mx-0"/>
  </div>

  <div class="w-full md:w-[50%]">
    <h1 class="text-white text-3xl md:text-5xl text-center font-bold mb-15">Plus A <span class="bg-gradient-to-r from-orange-500 to-red-500 text-transparent bg-clip-text font-bold hover:from-red-500 hover:to-orange-500 transition-all">Propos</span> De Moi</h1>
    <Propos/>
  </div>
</div>

</template>
<script setup>
import Card_H from './Card_H.vue';
import Propos from './Propos.vue';

// import Card from './Card.vue';
</script>
