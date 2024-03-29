<script setup>
import { PhoneIcon } from '@heroicons/vue/24/outline';
</script>

<template>
    <section class="pt-10 overflow-hidden bg-gray-200 md:pt-0 sm:pt-16 2xl:pt-16 border-b-[10px] border-sky-900">
        <div class="px-4 mx-auto sm:px-6 lg:px-8 max-w-7xl">
            <div class="grid items-center grid-cols-1 md:grid-cols-2">
                <div>
                    <h2 class="text-3xl font-bold leading-tight text-black sm:text-4xl lg:text-5xl">
                        We provide quick and reliable local locksmith services
                    </h2>
                    <p class="max-w-lg mt-3 text-base leading-relaxed text-gray-600 md:mt-8">
                        At Best Locksmith4You we are proud to be able to offer our customers exceptionally diverse range of professional locksmith services. Our mission is multifold, we can provide you with 24/7 locksmith services and also provide a range of services and supplies designed to improve the security of your home or business.
                        Our sales and service team bring a lifetime of security experience to the table and can show you how best to protect your family, your home, and your business in today growing crime. Our highly skilled locally based locksmiths can provide you with both commercial and residential locksmith services.
                    </p>
                    <p class="mt-4 text-xl text-gray-600 md:mt-8 w-96">
                        <a href="tel:01212854484" class="bg-yellow-400 text-gray-900 hover:bg-yellow-300 py-2 px-6 rounded-full text-lg font-semibold transition duration-300 ease-in-out transform hover:scale-105 hover:shadow-lg flex flex-row items-center justify-center gap-x-2 w-11/12">
                            <PhoneIcon class="h-6 w-6 mr-2" aria-hidden="true" /> 
                            Call Your Locksmiths Today!
                        </a>
                    </p>
                </div>
                <div class="relative">
                    <NuxtImg class="relative w-6/12 xl:max-w-lg mx-auto 2xl:origin-bottom 2xl:scale-110" src="/images/locksmith-services.webp" alt="" />
                </div>
            </div>
        </div>
    </section>
</template>