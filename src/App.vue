<script setup>
import { RouterLink,RouterView } from 'vue-router';
import Header from './components/Header.vue';
import Sidebar from './components/Sidebar.vue';
import Footer from './components/Footer.vue';
</script>

<template>
    <div>
      <Header />
        <!-- Sidebar and Main Content Container -->
      <div class="flex min-h-screen pt-20">
        <Sidebar />
        <!-- Main Content -->
        <main class="flex-1 ml-64 p-8">
          <RouterView />
        </main>
      </div>
    </div>
    <Footer />
</template>

<style scoped>

</style>
