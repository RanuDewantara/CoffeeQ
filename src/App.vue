<script setup>
import Navbar from './components/Navbar.vue'
import Home from "./components/Home.vue";
import About from "./components/About.vue";
import Coffee from "./components/Coffee.vue";
import NonCoffee from "./components/NonCoffee.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <Navbar />
	<Home />
	<About />
	<h1 id="menus" class="bg-[#0D0500] font-['Oxanium'] font-semibold text-center text-white text-[3em] pt-20">Menus</h1>
	<Coffee/>
	<NonCoffee/>
	<Contact/>
	<Footer/>
</template>