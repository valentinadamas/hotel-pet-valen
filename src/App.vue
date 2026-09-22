<script setup>
import { RouterView } from 'vue-router';
import DefaultLayout from './components/layout/DefaultLayout.vue';
import AppNavbar from './components/layout/AppNavbar.vue';
import AppSidebar from './components/layout/AppSidebar.vue';

</script>

<template>
  <DefaultLayout/>
  <RouterView/>
  <AppNavbar/>
  <AppSidebar/>
</template>
