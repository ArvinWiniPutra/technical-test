<template>
  <div class="overflow-x-hidden">
    <Navbar />
    <HeroSection />
    <ClientsSection />
    <FeaturesSection />
    <HelpingLocalBussiness />
    <DesignSiteFooter />
    <TeslaSection />
    <BlogSection />
    <DemoSection />
    <Footer />
  </div>
</template>

<script setup>
import Navbar from '@/components/landing/Navbar.vue';
import HeroSection from '@/components/landing/HeroSection.vue';
import ClientsSection from '@/components/landing/ClientsSection.vue';
import FeaturesSection from '@/components/landing/FeaturesSection.vue';
import HelpingLocalBussiness from '@/components/landing/HelpingLocalBussiness.vue';
import DesignSiteFooter from '@/components/landing/DesignSiteFooter.vue';
import TeslaSection from '../components/landing/TeslaSection.vue';
import BlogSection from '@/components/landing/BlogSection.vue';
import DemoSection from '../components/landing/DemoSection.vue';
import Footer from '@/components/landing/Footer.vue';
</script>