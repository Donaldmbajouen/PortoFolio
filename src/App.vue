<template>
  <div class="bg-[#101838]" id="top">
    <Nav/>
    <Section1/>
    <h1 class="text-white text-2xl sm:text-3xl md:text-4xl lg:text-5xl xl:text-6xl px-2 sm:px-3 md:px-4 lg:px-5 mb-3 sm:mb-4 md:mb-6 lg:mb-8 xl:mb-10 font-bold text-center md:text-left">Mes Services</h1>
    <div class="relative grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-2 sm:gap-3 md:gap-4 lg:gap-5 mb-6 sm:mb-8 md:mb-12 lg:mb-16 xl:mb-20 sm:justify-center overflow-hidden bg-[#101838] py-4 sm:py-6 md:py-8 lg:py-10 xl:py-12 px-2 sm:px-3 md:px-4 lg:px-5">
      <Card/>
      <Card/>
      <Card/>
    </div>
    <About class="mb-20"/>
    <div class="py-5 flex flex-col md:flex-row">
      <div class="w-full md:w-[50%] px-2 sm:px-3 md:px-5">
        <h1 class="text-white text-3xl sm:text-4xl md:text-5xl font-bold mb-5 sm:mb-8 md:mb-10 text-center md:text-left">Mes Competences</h1>
        <Skill/>
        <Skill/>
        <Skill/>
        <Skill/>
        <Skill/>
      </div>
      <div class="w-full md:w-[50%] px-2 sm:px-3 md:px-5">
        <h1 class="text-white text-3xl sm:text-4xl md:text-5xl font-bold mb-5 sm:mb-8 md:mb-10 text-center md:text-left">Experiences</h1>
        <Experience/>
        <Experience/>
      </div>
    </div>
    <div class="p-2 sm:p-3 md:p-5 mt-5 sm:mt-8 md:mt-10">
      <Projet/>
    </div>
    <Contact/>
</div>
<Footer/>
<a class="fixed bottom-5 right-5 bg-red-500 text-white p-3 rounded-full hover:bg-red-700" href="#top">
  <i class="fas fa-arrow-up"></i>
</a>
</template>


<script setup>
import About from './components/About.vue';
import Card from './components/Card.vue';
import Contact from './components/Contact.vue';
import Experience from './components/Experience.vue';
import Nav from './components/Nav.vue';
import Projet from './components/Projet.vue';
import Section1 from './components/Section1.vue';
import Skill from './components/Skill.vue';
import Footer from './components/Footer.vue';

</script>
