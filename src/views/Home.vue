<template>
  <div >
    <Banner />
    <AboutSection />
    <SpechSection />
    <RoadmapSection />
    <FaqSection />
    <!-- <FooterSection /> -->
  </div>
</template>

<script setup>
import Banner from '@/components/Home/Banner.vue'
import AboutSection from "./landingPartials/About.vue"
import SpechSection from "./landingPartials/Specs.vue"
import RoadmapSection from "./landingPartials/Roadmap.vue"
import FaqSection from "./landingPartials/Faq.vue"
import FooterSection from "@/layouts/default/DefaultFooter.vue"
</script>
