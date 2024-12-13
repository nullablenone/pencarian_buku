<script setup>
import Navbar from './components/Navbar.vue'
import FormSearch from './components/FormSearch.vue';
</script>

<template>
  <Navbar />

  <section class="flex flex-col items-center my-12">
    <h1 class="text-xl md:text-2xl: font-semibold mb-6">Temukan Buku Yang Kamu Mau</h1>
    <FormSearch />
  </section>
</template>
