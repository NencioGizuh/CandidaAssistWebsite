<script setup>
import Hero from './components/Hero.vue'
import Features from './components/Features.vue'
import CTA from './components/CTA.vue'
</script>

<template>
  <div class="min-h-screen bg-black">
    <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4">
      <div class="flex items-center justify-between">
        <div class="text-2xl font-bold text-white">Logo</div>
        <div class="flex justify-center items-center space-x-8">
          <a href="#" class="text-gray-300 hover:text-white">Features</a>
          <a href="#" class="text-gray-300 hover:text-white">About</a>
          <a href="#" class="text-gray-300 hover:text-white">Contact</a>
        </div>
        <div>
          <a href="#" class="inline-flex items-center px-4 py-2 border border-white text-sm font-medium rounded-md text-black bg-white hover:bg-gray-100">
            Download the App
          </a>
        </div>
      </div>
    </nav>
    
    <Hero />
    <Features />
    <CTA />
    
    <footer class="bg-black">
      <div class="max-w-7xl mx-auto px-4 py-12 sm:px-6 lg:px-8">
        <p class="text-center text-white">© 2024 Candida Assist. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>