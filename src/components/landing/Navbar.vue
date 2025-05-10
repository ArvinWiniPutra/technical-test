<template>
  <header class="border-b border-gray-100 bg-white">
    <div class="container mx-auto px-4 py-4 flex items-center justify-between">
      <div class="flex items-center">
        <img src="../../assets/logo.svg" alt="Nexcent" class="h-6" />
      </div>
      
      <nav class="hidden md:flex items-center space-x-8">
        <Button variant="ghost" class="text-gray-600 hover:text-green-500">Home</Button>
        <Button variant="ghost" class="text-gray-600 hover:text-green-500">Features</Button>
        <Button variant="ghost" class="text-gray-600 hover:text-green-500">Community</Button>
        <Button variant="ghost" class="text-gray-600 hover:text-green-500">Blog</Button>
        <Button variant="ghost" class="text-gray-600 hover:text-green-500">Pricing</Button>
      </nav>
      
      <div class="hidden md:block">
        <Button variant="default" class="bg-green-500 hover:bg-green-600 text-white">Register Now</Button>
      </div>
      
      <Button variant="ghost" class="md:hidden" @click="toggleMobileMenu">
        <MenuIcon class="h-6 w-6" />
      </Button>
    </div>
    
    <!-- Mobile Menu -->
    <div v-if="mobileMenuOpen" class="md:hidden py-4 px-4 border-t border-gray-100">
      <nav class="flex flex-col space-y-4">
        <Button variant="ghost" class="text-gray-600 hover:text-green-500 justify-start">Home</Button>
        <Button variant="ghost" class="text-gray-600 hover:text-green-500 justify-start">Features</Button>
        <Button variant="ghost" class="text-gray-600 hover:text-green-500 justify-start">Community</Button>
        <Button variant="ghost" class="text-gray-600 hover:text-green-500 justify-start">Blog</Button>
        <Button variant="ghost" class="text-gray-600 hover:text-green-500 justify-start">Pricing</Button>
        <Button variant="default" class="bg-green-500 hover:bg-green-600 text-white w-full">Register Now</Button>
      </nav>
    </div>
  </header>
</template>

<script setup>
import { ref } from 'vue';
import { Button } from '@/components/ui/button';
import { MenuIcon } from 'lucide-vue-next';

const mobileMenuOpen = ref(false);

const toggleMobileMenu = () => {
  mobileMenuOpen.value = !mobileMenuOpen.value;
};
</script>