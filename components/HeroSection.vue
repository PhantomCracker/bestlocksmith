<script setup>
import { PhoneIcon } from '@heroicons/vue/24/outline';
</script>

<template>
  <div class="relative bg-gradient-to-r from-purple-600 to-blue-600 h-screen text-white overflow-hidden mb-8">
    <div class="absolute inset-0">
      <NuxtImg src="/images/hero-locksmith.webp" alt="Locksmith Background" class="object-cover object-center w-full h-full" />
      <div class="absolute inset-0 bg-black opacity-70"></div>
    </div>
    
    <div class="relative z-10 flex flex-col justify-center items-center h-full text-center">
      <h1 class="text-5xl font-bold leading-tight mb-4 mt-16">Emergency Local Locksmith Near Me</h1>
      <p class="text-lg text-gray-200 mb-8 lg:w-1/2 sm:w-4/5 p-6"><span class="text-xl">Are you locked out? Don't panic!</span> <br/> Our locksmiths are available 24/7 to get you back inside quickly and affordably. Whether your lock is broken, you've been locked out of your house, or simply need a reliable locksmith nearby, we're the trusted choice for all residents.
        <br/> <br/>
        We offer fast, reliable service at competitive prices, so you can save money and get back to your day. Our local, expert locksmiths are here to help, no matter the time.
      </p>
      <a href="tel:01212854484" class="bg-yellow-400 text-gray-900 hover:bg-yellow-300 py-2 px-6 rounded-full text-lg font-semibold transition duration-300 ease-in-out transform hover:scale-105 hover:shadow-lg flex flex-row items-center justify-center gap-x-2">
        <PhoneIcon class="h-6 w-6 mr-2" aria-hidden="true" /> 
        Call Local Locksmith Now
      </a>
    </div>
  </div>
</template>