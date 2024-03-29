<script setup>
</script>

<template>
    <Html lang="en">
      <Head>
        <Meta name="description" :content="`24/7 emergency locksmith services in ${city}. We also provide a range of services and supplies designed to improve the security of your home or business`" />
        <Title>Emergency Locksmith in {{ city }}</Title>
      </Head>
    </Html>
    <NuxtLayout>
        <HeroSection />
        <OurServices />
        <AboutUs />
        <TestimonialsSection />
        <CallToAction />
        <TrustedSection />
    </NuxtLayout>
  </template>
  

<style lang="scss" scoped>
</style>