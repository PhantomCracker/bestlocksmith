<script setup>
import { PhoneIcon } from '@heroicons/vue/24/outline';
</script>

<template>
    <div class="bg-white">
      <div class="mx-auto max-w-7xl py-24 sm:px-6 sm:py-32 lg:px-8">
        <div class="relative justify-center isolate overflow-hidden bg-gray-900 px-6 pt-16 shadow-2xl sm:rounded-3xl sm:px-16 md:pt-24 lg:flex lg:gap-x-20 lg:px-24 lg:pt-0">
          <svg viewBox="0 0 1024 1024" class="absolute left-1/2 top-1/2 -z-10 h-[64rem] w-[64rem] -translate-y-1/2 [mask-image:radial-gradient(closest-side,white,transparent)] sm:left-full sm:-ml-80 lg:left-1/2 lg:ml-0 lg:-translate-x-1/2 lg:translate-y-0" aria-hidden="true">
            <circle cx="512" cy="512" r="512" fill="url(#759c1415-0410-454c-8f7c-9a820de03641)" fill-opacity="0.7" />
            <defs>
              <radialGradient id="759c1415-0410-454c-8f7c-9a820de03641">
                <stop stop-color="#7775D6" />
                <stop offset="1" stop-color="#E935C1" />
              </radialGradient>
            </defs>
          </svg>
          <div class="mx-auto max-w-2xl text-center lg:mx-0 lg:flex-auto lg:py-32">
            <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">Local Locksmith Near You 24/7</h2>
            <p class="mt-6 text-lg leading-8 text-gray-300">
              We pride ourselves on being the foremost provider of comprehensive locksmith solutions conveniently located near you, available round-the-clock. With a steadfast commitment to excellence and customer satisfaction, our team of certified locksmith professionals stands ready to address all your residential, and commercial locksmith needs with precision and efficiency.
            </p>
            <div class="mt-10 flex items-center justify-center gap-x-6 mb-4 lg:mb-0">
              <a href="tel:01212854484" class="bg-yellow-400 text-gray-900 hover:bg-yellow-300 py-2 px-6 rounded-full text-lg font-semibold transition duration-300 ease-in-out transform hover:scale-105 hover:shadow-lg flex flex-row items-center justify-center gap-x-2">
                <PhoneIcon class="h-6 w-6 mr-2" aria-hidden="true" /> 
                Call Your Locksmith Expert
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>