<template>
  <section class="py-16 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-2xl md:text-3xl font-bold text-center mb-4">
        Caring is the new marketing
      </h2>
      <p class="text-gray-600 text-center mb-16 max-w-2xl mx-auto">
        The Nexcent blog is the best place to read about the latest membership insights, trends and more. See who's joining the community, read about how our community are increasing their membership income and lots more.
      </p>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <Card class="bg-white shadow-sm hover:shadow-md transition-shadow overflow-hidden">
          <img src="../../assets/image-18.jpg" alt="Blog 1" class="w-full h-48 object-cover" />
          <CardContent class="p-6">
            <div class="bg-gray-100 rounded-lg p-4 -mt-12 mx-auto relative w-5/6 mb-4">
              <h3 class="text-lg font-semibold text-center">Creating Streamlined Safeguarding Processes with OneRen</h3>
            </div>
            <Button variant="link" class="text-green-500 hover:text-green-600 mx-auto block">
              Read More →
            </Button>
          </CardContent>
        </Card>
        
        <Card class="bg-white shadow-sm hover:shadow-md transition-shadow overflow-hidden">
          <img src="../../assets/image-19.jpg" alt="Blog 2" class="w-full h-48 object-cover" />
          <CardContent class="p-6">
            <div class="bg-gray-100 rounded-lg p-4 -mt-12 mx-auto relative w-5/6 mb-4">
              <h3 class="text-lg font-semibold text-center">What are your safeguarding responsibilities and how can you manage them?</h3>
            </div>
            <Button variant="link" class="text-green-500 hover:text-green-600 mx-auto block">
              Read More →
            </Button>
          </CardContent>
        </Card>
        
        <Card class="bg-white shadow-sm hover:shadow-md transition-shadow overflow-hidden">
          <img src="../../assets/image-20.jpg" alt="Blog 3" class="w-full h-48 object-cover" />
          <CardContent class="p-6">
            <div class="bg-gray-100 rounded-lg p-4 -mt-12 mx-auto relative w-5/6 mb-4">
              <h3 class="text-lg font-semibold text-center">Revamping the Membership Model with Triathlon Australia</h3>
            </div>
            <Button variant="link" class="text-green-500 hover:text-green-600 mx-auto block">
              Read More →
            </Button>
          </CardContent>
        </Card>
      </div>
    </div>
  </section>
</template>

<script setup>
import { Button } from '@/components/ui/button';
import { Card, CardContent } from '@/components/ui/card';
</script>