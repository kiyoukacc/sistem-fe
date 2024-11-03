<!-- views/AboutUsView.vue -->
<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import Authors from '@/components/Authors.vue/Author1.vue'
</script>

<template>
  <MainLayout>
  <Authors/> <!-- Menampilkan isi dari komponen AboutUs.vue di dalam MainLayout -->
  </MainLayout>
</template>