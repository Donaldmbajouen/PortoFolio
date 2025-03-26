<template>
  <div class="bg-[#101838]">
    <Nav/>
    <Section1/>
    <h1 class="text-white text-5xl px-5 mb-10 font-bold">Mes Services</h1>
    <div class="relative grid grid-cols-3 mb-20 justify-center overflow-hidden bg-[#101838] py-12 sm:py-12">
      <Card/>
      <Card/>
      <Card/>
    </div>
    <About class="mb-20"/>
    <div class="py-5 flex">
      <div class="w-[50%] px-5 ">
        <h1 class="text-white text-5xl font-bold mb-10">Mes Competences</h1>
        <Skill/>
        <Skill/>
        <Skill/>
        <Skill/>
        <Skill/>
      </div>
      <div class="w-[50%] px-5">
        <h1 class="text-white text-5xl font-bold mb-10 text-center">Experiences</h1>
        <Experience/>
        <Experience/>
      </div>
    </div>
    <div class="p-5 mt-10">
      <Projet/>
    </div>
    <Contact/>
</div>
<Footer/>
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
