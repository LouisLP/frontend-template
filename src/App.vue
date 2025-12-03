<script setup>
import { Icon } from '@iconify/vue'

import Footer from '@/components/ui/BaseFooter.vue'
import Navbar from '@/components/ui/BaseNavbar.vue'
</script>

<template>
  <Navbar />

  <main>
    <RouterView />
  </main>

  <div class="space-y-6">
    <!-- Tailwind -->
    <h1 class="text-3xl font-bold underline">
      Hello World!
    </h1>

    <!-- DaisyUI -->
    <button class="btn btn-primary">
      Click Me
    </button>

    <!-- Iconify -->
    <Icon icon="mdi:home" class="size-6 text-gray-700" />
  </div>

  <Footer />
</template>
