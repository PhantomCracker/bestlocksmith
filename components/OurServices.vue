<script setup>
import { HomeIcon, CheckBadgeIcon, ClockIcon } from "@heroicons/vue/24/solid"
</script>

<template>
    <div class="grid md:grid-cols-3 max-w-screen-lg mx-auto gap-10 px-5 mb-8">
        <div class="flex gap-4 items-center flex-col ">
            <span class="text-yellow-400 bg-yellow-400/10 p-3 rounded-full">
                <HomeIcon class="h-6 w-6" aria-hidden="true" />
            </span>
            <div class="flex flex-col items-center">
                <h3 class="font-semibold text-xl">Residential Locksmith Services</h3>
                <p class="mt-1 text-gray-500 text-center">
                    Locked out of your house? Our residential locksmith services have you covered. We specialize in providing swift and reliable lockout assistance for homeowners. Whether you've misplaced your keys or experienced a lock malfunction, our team is here to help you regain access to your home promptly and safely.
                </p>
            </div>
        </div>
        <div class="flex gap-4 items-center flex-col ">
            <span class="text-yellow-400 bg-yellow-400/10 p-3 rounded-full">
                <CheckBadgeIcon class="h-6 w-6" aria-hidden="true" />
            </span>
            <div class="flex flex-col items-center">
                <h3 class="font-semibold text-xl">Top Rated Local Locksmiths</h3>
                <p class="mt-1 text-gray-500 text-center">
                    Discover top-rated residential locksmith services right in your neighborhood. Our team of highly skilled locksmith professionals is dedicated to providing the highest quality service and unparalleled customer satisfaction for all your home security needs.
                </p>
            </div>
        </div>
        <div class="flex gap-4 items-center flex-col ">
            <span class="text-yellow-400 bg-yellow-400/10 p-3 rounded-full">
                <ClockIcon class="h-6 w-6" aria-hidden="true" />
            </span>
            <div class="flex flex-col items-center">
                <h3 class="font-semibold text-xl">Emergency Locksmith Services</h3>
                <p class="mt-1 text-gray-500 text-center">
                    When emergencies strike, trust our team to provide prompt and dependable solutions to your urgent locksmith needs. Our dedicated team of emergency locksmith professionals is available around the clock 24/7, ready to assist you whenever and wherever you need us.
                </p>
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