<script setup lang="ts">
import { RouterView } from 'vue-router'
import NavBar from '../src/components/NavBar.vue'
</script>

<template>
  <div class="main">
    <NavBar />
    <RouterView />
  </div>
</template>

<style scoped>
*{
  margin: 0;
  padding: 0;
}
.main{
  background: #1f242d;
}
</style>
