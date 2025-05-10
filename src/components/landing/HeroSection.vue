<template>
  <section class="py-16 md:py-24 bg-gray-50">
    <div class="container mx-auto px-4">
      <div class="flex flex-col md:flex-row items-center">
        <div class="md:w-1/2 mb-10 md:mb-0 md:pr-10">
          <h1 class="text-3xl md:text-4xl lg:text-5xl font-bold text-gray-800 mb-4">
            Lessons and insights <span class="text-green-500">from 8 years</span>
          </h1>
          <p class="text-gray-600 mb-8">
            Where to grow your business as a photographer: site or social media?
          </p>
          <Button class="bg-green-500 hover:bg-green-600 text-white px-8 py-2">
            Register
          </Button>
        </div>
        <div class="md:w-1/2">
          <img 
            src="../../assets/hero-section.svg" 
            alt="Hero Illustration" 
            class="w-full h-auto"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { Button } from '@/components/ui/button';
</script>