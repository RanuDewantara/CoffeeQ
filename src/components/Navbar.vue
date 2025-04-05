<template>
  <nav class="fixed left-0 right-0 w-full z-[9999] top-0 start-0 bg-[#2C0000]">
    <div class="max-w-7xl flex flex-wrap items-center justify-between mx-auto md:px-5">
      <a href="#" class="flex items-center space-x-3 rtl:space-x-reverse ms-5 md:ms-0">
	      <img src="../assets/img/CoffeeQ.png" alt="CoffeeQ" class="h-24 p-2">
      </a>
      <button data-collapse-toggle="navbar-solid-bg" type="button" class="inline-flex items-center p-2 me-5 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-[#1C0000] focus:bg-[#100000]" aria-controls="navbar-solid-bg" aria-expanded="false">
	      <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
          <path stroke="white" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
        </svg>
      </button>
      <div class="bg-[#1A0000] hidden w-full px-6 md:block md:px-0 md:w-auto md:bg-transparent" id="navbar-solid-bg">
        <ul class="flex flex-col font-['ProstoOne'] font-medium text-[11pt] mt-0 rounded-lg md:space-x-8 rtl:space-x-reverse md:flex-row md:border-0 md:bg-transparent lg:text-base xl:text-lg">
          <li>
            <a href="#" class="block py-2 px-3 md:p-0 text-gray-400 rounded-sm md:border-0 hover:text-white">Home</a>
          </li>
	        <li>
            <a href="#about" class="block py-2 px-3 md:p-0 text-gray-400 rounded-sm md:border-0 hover:text-white">About Us</a>
          </li>
          <li>
            <a href="#menus" class="block py-2 px-3 md:p-0 text-gray-400 rounded-sm md:border-0 hover:text-white">Coffees</a>
          </li>
	        <li>
            <a href="#noncoffees" class="block py-2 px-3 md:p-0 text-gray-400 rounded-sm md:border-0 hover:text-white">Non-Coffees</a>
          </li>
	        <li>
            <a href="#contact" class="block py-2 px-3 md:p-0 text-gray-400 rounded-sm md:border-0 hover:text-white">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<script lang="ts" setup>
</script>