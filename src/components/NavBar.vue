<script setup lang="ts">

</script>

<template>
  <header class="header">
    <router-link to="#" class="logo">Protfolio.</router-link>
    <nav class="navbar">
      <router-link to="/" class="link active item" style="--i: 1">Home</router-link>
      <router-link to="" class="link active item" style="--i: 2">Moments</router-link>
      <router-link to="" class="link item" style="--i: 3">Articles</router-link>
      <router-link to="" class="link item" style="--i: 4">Photos</router-link>
      <router-link to="" class="link item" style="--i: 5">Music</router-link>
      <router-link to="" class="link item" style="--i: 6">About</router-link>
    </nav>
  </header>
</template>

<style scoped>
.header {
  position: fixed;
  top: 0;
  left: 0;
  padding: 20px;
  width: 100%;
  background-color: transparent;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 100;
}
.header .logo{
  font-size: 25px;
  color: #fff;
  text-decoration: none;
  font-weight: 600;
  cursor: default;
}
.header .navbar .link{
  display: inline-block;
  font-size: 18px;
  color: #fff;
  text-decoration: none;
  font-weight: 500;
  margin-left: 35px;
}
.header .navbar .link:hover,
.navbar .navbar .link .active{
  color: #b7b2a9;
}
</style>
