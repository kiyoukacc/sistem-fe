<!-- views/AboutUsView.vue -->
<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import BlogPost from '@/components/BlogPost.vue'
import Join from '@/components/Join.vue'
</script>

<template>
  <MainLayout>
  <BlogPost/> <!-- Menampilkan isi dari komponen AboutUs.vue di dalam MainLayout -->
  <Join/>
  </MainLayout>
</template>