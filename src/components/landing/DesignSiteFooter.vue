<template>
  <section class="py-16 bg-white">
    <div class="container mx-auto px-4">
      <div class="flex flex-col md:flex-row items-center">
        <div class="md:w-1/2 mb-10 md:mb-0">
          <img src="../../assets/pana.svg" alt="Mobile App" class="w-full h-auto" />
        </div>
        <div class="md:w-1/2 md:pl-12">
          <h2 class="text-2xl md:text-3xl font-bold mb-4">
            How to design your site footer like we did
          </h2>
          <p class="text-gray-600 mb-6">
            Donec a eros justo. Fusce egestas tristique ultrices. Nam tempor, augue nec tincidunt molestie, massa nunc varius arcu, at scelerisque elit erat a magna. Donec quis erat at libero ultrices mollis. In hac habitasse platea dictumst. Vivamus vehicula leo dui, at porta nisi facilisis finibus.
          </p>
          <Button class="bg-green-500 hover:bg-green-600 text-white">
            Learn More
          </Button>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { Button } from '@/components/ui/button';
</script>