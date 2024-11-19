<script setup>
const features = [
  {
    title: 'Manage your Candida',
    description: 'Check your sleep quality, Stress levels and glycemic load',
    icon: '⚡'
  },
  {
    title: 'Predictive Analysis',
    description: 'Our analysis helps you keep track of potential yeast overgrowth',
    icon: '📊'
  },
  {
    title: 'Keep Track',
    description: 'Look at how your overall score is to prevent yeast overgrowth from happening',
    icon: '📅'
  }
]
</script>

<template>
  <div class="py-12 bg-black">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center">
        <h2 class="text-3xl font-extrabold text-white sm:text-4xl">
          Features
        </h2>
        <p class="mt-4 text-xl text-gray-300">
          Everything you need to build amazing products
        </p>
      </div>

      <div class="mt-20">
        <div class="grid grid-cols-1 gap-8 sm:grid-cols-2 lg:grid-cols-3">
          <div v-for="feature in features" :key="feature.title" class="pt-6">
            <div class="flow-root bg-gray-900 rounded-lg px-6 pb-8">
              <div class="-mt-6">
                <div class="inline-flex items-center justify-center p-3 bg-white rounded-md shadow-lg text-3xl">
                  {{ feature.icon }}
                </div>
                <h3 class="mt-8 text-lg font-medium text-white tracking-tight">{{ feature.title }}</h3>
                <p class="mt-5 text-base text-gray-300">
                  {{ feature.description }}
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>