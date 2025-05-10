<template>
  <section class="py-16 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-2xl md:text-3xl font-bold text-center mb-12">Our Clients</h2>
      <div class="grid grid-cols-3 md:grid-cols-7 gap-8 items-center justify-items-center">
        <img v-for="(logo, index) in clientLogos" :key="index" :src="logo" alt="Client Logo" class="h-8 md:h-10 opacity-60 hover:opacity-100 transition-opacity" />
      </div>
    </div>
  </section>
</template>

<script setup>
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