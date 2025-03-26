
<template>
    <header class="lg:px-16 px-4 flex flex-wrap items-center py-4 shadow-md bg-[#101838] shadow-gray-800 border-b-1 border-gray-800">
        <div class="flex-1 flex justify-between items-center">
            <a href="#" class="text-4xl bg-gradient-to-r from-orange-500 to-red-500 text-transparent bg-clip-text font-bold hover:from-red-500 hover:to-orange-500 transition-all duration-300">PORTOFOLIO</a>
        </div>

        <label for="menu-toggle" class="pointer-cursor md:hidden block">
        <svg class="fill-current text-red-500"
            xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20">
            <title>menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
        </svg>
        </label>
        <input class="hidden" type="checkbox" id="menu-toggle" />

        <div class="hidden md:flex md:items-center md:w-auto w-full" id="menu">
            <nav>
                <ul class="md:flex items-center justify-between text-xl font-semibold text-white pt-4 md:pt-0">
                    <li><a class="md:p-4 py-3 px-0 block text-red-500" href="#">Accueil</a></li>
                    <li><a class="md:p-4 py-3 px-0 block hover:text-red-500" href="#">Services</a></li>
                    <li><a class="md:p-4 py-3 px-0 block hover:text-red-500" href="#">Projets</a></li>
                    <li><a class="md:p-4 py-3 px-0 block hover:text-red-500" href="#">A Propos</a></li>
                    <li><a class="md:p-4 py-3 px-0 hover:text-red-500 block md:mb-0 mb-2" href="#">Contact </a></li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script setup>
</script>
