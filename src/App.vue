<template>
  <v-app>
    <v-main>
        <NavBar />
        <router-view />
      </v-main>
      
  
  </v-app>
</template>

<script setup>
  
import NavBar from './components/Navbar.vue';

</script>
