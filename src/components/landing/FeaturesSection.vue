<template>
  <section class="py-16 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-2xl md:text-3xl font-bold text-center mb-4">
        Manage your entire community in a single system
      </h2>
      <p class="text-gray-600 text-center mb-16 max-w-2xl mx-auto">
        Who is Nextcent suitable for?
      </p>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <Card class="bg-white border-none shadow-[0_4px_6px_-1px_rgba(0,0,0,0.1)] hover:shadow-[0_6px_8px_-1px_rgba(0,0,0,0.15)] transition-shadow">
          <CardContent class="p-6 text-center">
            <div class="flex justify-center mb-4">
              <img src="../../assets/membership.svg" alt="Membership" class="h-16 w-16" />
            </div>
            <h3 class="text-xl font-semibold mb-3">Membership Organizations</h3>
            <p class="text-gray-600">
              Our membership management software provides full automation of membership renewals and payments
            </p>
          </CardContent>
        </Card>
        
        <Card class="bg-white border-none shadow-[0_4px_6px_-1px_rgba(0,0,0,0.1)] hover:shadow-[0_6px_8px_-1px_rgba(0,0,0,0.15)] transition-shadow">
          <CardContent class="p-6 text-center">
            <div class="flex justify-center mb-4">
              <img src="../../assets/association.svg" alt="Association" class="h-16 w-16" />
            </div>
            <h3 class="text-xl font-semibold mb-3">National Associations</h3>
            <p class="text-gray-600">
              Our membership management software provides full automation of membership renewals and payments
            </p>
          </CardContent>
        </Card>
        
        <Card class="bg-white border-none shadow-[0_4px_6px_-1px_rgba(0,0,0,0.1)] hover:shadow-[0_6px_8px_-1px_rgba(0,0,0,0.15)] transition-shadow">
          <CardContent class="p-6 text-center">
            <div class="flex justify-center mb-4">
              <img src="../../assets/clubs-and-groups.svg" alt="Clubs" class="h-16 w-16" />
            </div>
            <h3 class="text-xl font-semibold mb-3">Clubs And Groups</h3>
            <p class="text-gray-600">
              Our membership management software provides full automation of membership renewals and payments
            </p>
          </CardContent>
        </Card>
      </div>
      
      <!-- Pixelgrade Section -->
      <div class="mt-24 flex flex-col md:flex-row items-center">
        <div class="md:w-1/2 mb-10 md:mb-0">
          <img src="../../assets/mobile-login.svg" alt="Pixelgrade" class="w-full h-auto" />
        </div>
        <div class="md:w-1/2 md:pl-12">
          <h2 class="text-2xl md:text-3xl font-bold mb-4">
            The unseen of spending three years at Pixelgrade
          </h2>
          <p class="text-gray-600 mb-6">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
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
import { Card, CardContent } from '@/components/ui/card';
</script>