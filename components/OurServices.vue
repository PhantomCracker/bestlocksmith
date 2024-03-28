<script setup>
import { HomeIcon, CheckBadgeIcon, ClockIcon } from "@heroicons/vue/24/outline"
</script>

<template>
    <div class="grid md:grid-cols-3 max-w-screen-lg mx-auto gap-10 px-5 mb-8">
        <div class="flex gap-4 items-center flex-col ">
            <span class="text-violet-600 bg-violet-500/10 p-3 rounded-full">
                <HomeIcon class="h-6 w-6" aria-hidden="true" />
            </span>
            <div class="flex flex-col items-center">
                <h3 class="font-semibold text-xl">Residential Locksmith Services</h3>
                <p class="mt-1 text-gray-500 text-center"> You don't need to be an expert to use our plugin. Our expressive API is
                    readable and well documented.</p>
            </div>
        </div>
        <div class="flex gap-4 items-center flex-col ">
            <span class="text-violet-600 bg-violet-500/10 p-3 rounded-full">
                <CheckBadgeIcon class="h-6 w-6" aria-hidden="true" />
            </span>
            <div class="flex flex-col items-center">
                <h3 class="font-semibold text-xl">Top Rated Local Locksmiths</h3>
                <p class="mt-1 text-gray-500 text-center"> You can make sure your website or app is highly performant with a built-in
                    system to help you optimize.</p>
            </div>
        </div>
        <div class="flex gap-4 items-center flex-col ">
            <span class="text-violet-600 bg-violet-500/10 p-3 rounded-full">
                <ClockIcon class="h-6 w-6" aria-hidden="true" />
            </span>
            <div class="flex flex-col items-center">
                <h3 class="font-semibold text-xl">Emergency Locksmith Services</h3>
                <p class="mt-1 text-gray-500 text-center"> Our plugins do not have any external dependencies so our plugin has the
                    minimal footprint possible.</p>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
svg {
    width: 80px;
    height: 80px;
}
</style>