<!-- views/AboutUsView.vue -->
<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import Privacy from '@/components/Privacy.vue'
</script>

<template>
  <MainLayout>
  <Privacy/> <!-- Menampilkan isi dari komponen AboutUs.vue di dalam MainLayout -->
  </MainLayout>
</template>