<script setup>
import { RouterView } from 'vue-router'
import Header from './components/Header/Header.vue';


</script>

<template>
  <div class="ok">
    <Header />
    <RouterView />
    <Footer />
  </div>
</template>