<template>
  <div
    class="group relative cursor-pointer overflow-hidden hover:border-2 hover:border-red-500 mb-10 bg-white px-4 md:px-6 lg:px-8 pt-4 md:pt-6 lg:pt-8 pb-4 md:pb-6 lg:pb-8 shadow-xl ring-1 ring-gray-900/5 transition-all duration-300 hover:-translate-y-1 hover:shadow-2xl w-full sm:max-w-[280px] md:max-w-[320px] lg:max-w-[360px] rounded-lg">
      <span class="absolute top-4 md:top-6 lg:top-8 left-1/2 -translate-x-1/2 z-0 h-16 md:h-16 lg:h-20 w-16 md:w-16 lg:w-20 rounded-full bg-black transition-all duration-300 group-hover:scale-[10]"></span>
      <div class="relative z-10 w-full">
         <div class="flex flex-col items-center justify-center">
            <span class="grid h-16 md:h-16 lg:h-20 w-16 md:w-16 lg:w-20 place-items-center rounded-full bg-red-500 transition-all duration-300 group-hover:bg-red-500">
              <i class="fas fa-user text-white text-3xl md:text-3xl lg:text-4xl"></i>
            </span>
            <p class="text-red-500 font-bold text-xl md:text-xl lg:text-2xl mt-4 md:mt-3">Developpement Web</p>
          </div>
          <div
            class="space-y-4 md:space-y-4 lg:space-y-6 pt-4 md:pt-4 lg:pt-5 text-base md:text-base lg:text-lg leading-relaxed text-gray-600 transition-all duration-300 group-hover:text-white/90">
            <p>Perfect for learning how the framework works, prototyping a new idea, or creating a demo to sharenline.</p>
          </div>
        </div>
  </div>
</template>
<script setup>

</script>
