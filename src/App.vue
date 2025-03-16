<template>
  <div class="bg-gray-900">
    <Nav/>

    <div class="bg-purple-600 transition-2s animate-pulse p-8 w-[300px] h-[300px] blur-[250px] absolute rounded-full"></div>
    <!-- <div class="bg-gradient-to-r from-purple-600 to-red-600 animate-pulse p-8 w-[300px] h-[300px] blur-[150px] absolute rounded-full"></div> -->
    <!-- <div class="bg-red-600 p-5 w-20 h-20 rotate-45 blur absolute top-150 left-180"></div>
    <div class="bg-red-600 p-5 w-20 h-20 blur absolute top-150 left-180"></div> -->
    <div class="flex mb-20 bg-gray-900 p-15">
      <div class="w-5xl">
        <div class="p-20">
          <h1 class="text-white text-4xl font-semibold">Hello, Je Suis <span class="text-5xl bg-gradient-to-r from-orange-500 to-red-500 text-transparent bg-clip-text font-bold hover:from-red-500 hover:to-orange-500 transition-all duration-300">DONALD NJEMI</span></h1>
          <p class="w-2xl mt-5 text-xl py-3 text-white">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Et itaque ea similique quae id obcaecati iusto fuga, officiis optio blanditiis ipsa necessitatibus architecto laboriosam nesciunt. Sunt molestias dolor ad placeat?</p>
          <div class="mt-5">
            <button class="inline-block px-7 py-3 overflow-hidden text-xl font-semibold transition-transform rounded-full group text text-white bg-transparent border-red-500 border-2 hover:bg-red-600 hover:text-white">
              <span ><i class="fas fa-download text-white"></i>  Telecharger mon cv</span>
            </button>
          </div>
        </div>
      </div>
      <div class="">
        <div class="w-full relative">
          <img class="shadow-2xl rounded-full shadow-red-500 animate-[spin_12s_linear_infinite] absolute left-0 right-0  lg:max-w-[65%] max-w-[60%] mx-auto" src="./images/img1.jpg" />
          <img class="relative rounded-full z-10 lg:max-w-[70%] max-w-[60%] mx-auto outline outline-[.3rem] outline-offset-[.1rem] outline-red-500" src="./images/img1.jpg" />
        </div>
      </div>
    </div>
    <h1 class="text-white text-5xl px-5 font-bold">Mes Services</h1>
    <div class="relative grid grid-cols-3 justify-center overflow-hidden bg-gray-900 py-12 sm:py-12">
      <Card/>
      <Card/>
      <Card/>
    </div>
    <About/>
</div>
</template>


<script setup>
import About from './components/About.vue';
import Card from './components/Card.vue';
import Nav from './components/Nav.vue';

</script>
