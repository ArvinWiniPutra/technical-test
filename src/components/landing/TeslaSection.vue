<template>
  <section class="py-2 bg-[#F5F7FA]">
    <div class="container mx-auto px-4">
      <div class="p-8 md:p-12">
        <div class="flex flex-col md:flex-row items-center">
          <div class="md:w-1/3 md:mb-0 flex justify-center">
            <img src="../../assets/image-9.png" alt="Tesla" class="h-auto" />
          </div>
          <div class="md:w-2/3 md:pl-8 text-white">
            <p class="mb-6 text-gray-600">
              Maecenas dignissim justo eget nulla rutrum molestie. Maecenas lobortis sem dui, vel rutrum risus tincidunt ullamcorper. Proin eu enim metus. Vivamus sed libero ornare, tristique quam in, gravida enim. Nullam ut molestie arcu, at hendrerit elit. Morbi laoreet elit at ligula molestie, nec molestie mi blandit. Suspendisse cursus tellus sed augue ultrices, quis tristique nulla sodales. Suspendisse eget lorem eu turpis vestibulum pretium. Suspendisse potenti. Quisque malesuada enim sapien, vitae placerat ante feugiat eget.
            </p>
            <div class="flex items-center">
              <!-- <img src="/avatar.jpg" alt="Avatar" class="h-12 w-12 rounded-full mr-4" /> -->
              <div>
                <p class="font-semibold text-[#4CAF4F]">Tim Smith</p>
                <p class="text-sm text-gray-400">British Dragon Boat Racing Association</p>
              </div>
            </div>
            <div class="mt-8">
              <div class="flex items-center justify-between">
                <div class="flex space-x-4 flex-grow">
                  <img v-for="(logo, index) in clientLogos" :key="index" :src="logo" alt="Client Logo" class="h-8 opacity-60 hover:opacity-100 transition-opacity" />
                </div>
                <a href="#" class="text-[#4CAF4F] hover:underline font-medium whitespace-nowrap ml-4">
                  Meet all customers →
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { Button } from '@/components/ui/button';

// Import all client logos individually
import client1 from '../../assets/client-1.svg';
import client2 from '../../assets/client-2.svg';
import client3 from '../../assets/client-3.svg';
import client4 from '../../assets/client-4.svg';
import client5 from '../../assets/client-5.svg';
import client6 from '../../assets/client-6.svg';
import client7 from '../../assets/client-7.svg';

// Create an array of the imported logos
const clientLogos = [
  client1,
  client2,
  client3,
  client4,
  client5,
  client6,
  client7
];
</script>