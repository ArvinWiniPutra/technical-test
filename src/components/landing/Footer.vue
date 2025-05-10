<template>
  <footer class="bg-gray-900 text-white py-12">
    <div class="container mx-auto px-4">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
        <div>
          <div class="flex items-center mb-6">
            <img :src="logoWhite" alt="Nexcent" class="h-8" />
          </div>
          <p class="text-gray-400 mb-4">
            Copyright © 2023 Nexcent ltd.<br />
            All rights reserved
          </p>
          <div class="flex space-x-4">
            <a href="#" class="text-gray-400 hover:text-white">
              <FacebookIcon class="h-5 w-5" />
            </a>
            <a href="#" class="text-gray-400 hover:text-white">
              <TwitterIcon class="h-5 w-5" />
            </a>
            <a href="#" class="text-gray-400 hover:text-white">
              <InstagramIcon class="h-5 w-5" />
            </a>
            <a href="#" class="text-gray-400 hover:text-white">
              <LinkedinIcon class="h-5 w-5" />
            </a>
          </div>
        </div>
        
        <div>
          <h3 class="text-lg font-semibold mb-4">Company</h3>
          <ul class="space-y-2">
            <li><a href="#" class="text-gray-400 hover:text-white">About us</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Blog</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Contact us</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Pricing</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Testimonials</a></li>
          </ul>
        </div>
        
        <div>
          <h3 class="text-lg font-semibold mb-4">Support</h3>
          <ul class="space-y-2">
            <li><a href="#" class="text-gray-400 hover:text-white">Help center</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Terms of service</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Legal</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Privacy policy</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Status</a></li>
          </ul>
        </div>
        
        <div>
          <h3 class="text-lg font-semibold mb-4">Stay up to date</h3>
          <div class="flex">
            <Input 
              type="email" 
              placeholder="Your email address" 
              class="bg-gray-800 border-gray-700 text-white"
            />
            <Button class="ml-2 bg-green-500 hover:bg-green-600">
              <SendIcon class="h-4 w-4" />
            </Button>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup>
import { Button } from '@/components/ui/button';
import { Input } from '@/components/ui/input';
import { FacebookIcon, TwitterIcon, InstagramIcon, LinkedinIcon, SendIcon } from 'lucide-vue-next';
import logoWhite from '@/assets/logo-white.svg';
</script>