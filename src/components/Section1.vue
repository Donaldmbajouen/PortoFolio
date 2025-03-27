<template>
    <div class="bg-purple-500 animate-pulse p-8 w-[300px] h-[300px] blur-[250px] absolute rounded-full"></div>
    <div class="bg-purple-500 animate-pulse p-8 w-[300px] h-[300px] blur-[250px] absolute rounded-full"></div>
    <div class="flex flex-col lg:flex-row mb-20 bg-[#101838] p-4 lg:p-15">
      <div class="w-full lg:w-1/2">
        <div class="p-4 lg:p-20 md:p-10">
          <h1 class="text-white text-2xl lg:text-4xl md:text-3xl font-semibold text-center lg:text-left">
            Hello, Je Suis 
            <span class="text-3xl lg:text-5xl md:text-4xl bg-gradient-to-r from-orange-500 to-red-500 text-transparent bg-clip-text font-bold hover:from-red-500 hover:to-orange-500 transition-all duration-300">
              DONALD NJEMI
            </span>
          </h1>
          <p class="w-full mt-5 text-sm lg:text-xl md:text-lg py-3 text-white text-center lg:text-left">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Et itaque ea similique quae id obcaecati iusto fuga, officiis optio blanditiis ipsa necessitatibus architecto laboriosam nesciunt. Sunt molestias dolor ad placeat?
          </p>
          <div class="mt-5 text-center lg:text-left">
            <button class="px-4 lg:px-7 md:px-5 py-2 lg:py-3 pointer-cursor text-sm lg:text-xl md:text-lg font-semibold transition-transform rounded-full text-white bg-transparent border-red-500 border-2 hover:bg-red-600 hover:text-white">
              <span><i class="fas fa-download text-white"></i> Telecharger mon cv</span>
            </button>
          </div>
        </div>
      </div>
      <div class="w-full lg:w-1/2 mt-10 lg:mt-0">
        <div class="relative w-full flex justify-center items-center">
          <img 
            class="shadow-2xl rounded-full shadow-2xl shadow-red-500 animate-[spin_12s_linear_infinite] absolute w-[55%] lg:w-[65%]" 
            src="../images/img1.jpg" 
          />
          <img 
            class="relative rounded-full z-10 w-[60%] lg:w-[70%] outline outline-[.3rem] outline-offset-[.1rem] outline-red-500" 
            src="../images/img1.jpg" 
          />
        </div>
      </div>
    </div>
</template>

<script setup>
</script>
