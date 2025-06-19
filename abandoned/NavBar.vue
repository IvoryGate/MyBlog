<script setup lang="ts">

</script>

<template>
  <div class="nav">
    <ul>
      <li><router-link to="/">HOME</router-link></li>
      <li><router-link to="">INTRODUCTION</router-link></li>
      <li><router-link to="">NEWS</router-link></li>
      <li><router-link to="">ARTICLE</router-link></li>
      <li><router-link to="">LIFE</router-link></li>
      <li><router-link to="/about">ABOUT</router-link></li>
      <li class="nav-box"></li>
    </ul>
  </div>
</template>

<style scoped>
*{
  margin: 0;
  padding: 0;
}
.nav{
  width: 100%;
  height: 50px;
  position: fixed;
  top: 0;
  box-shadow: 0 5px 20px rgba(0, 0, 0, 0.5);
  background-color: #fff;
}
.nav ul{
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  right: 5%;
}
.nav ul li{
  width: 100%;
  text-align: center;
  list-style: none;
}
.nav .nav-box{
  position: absolute;
  bottom: 0;
  left: calc((100% / 6)*-1);
  width: calc((100% / 6)*1);
  height: 5px;
  transition: .5s;
}
.nav ul li a{
  color: rgb(70, 100, 180);
  font: 100 20px "JetBrains Mono ExtraBold";
  display: block;
  width: 100%;
  height: 100%;
  line-height: 70px;
  text-decoration: none;
}
.nav ul li:nth-child(1):hover~.nav-box{
  left: calc(100% / 6 *0);
  background-color: #b45252;
}
.nav ul li:nth-child(2):hover~.nav-box{
  left: calc(100% / 6 *1);
  background-color: #b45252;
}
.nav ul li:nth-child(3):hover~.nav-box{
  left: calc(100% / 6 *2);
  background-color: #b45252;
}
.nav ul li:nth-child(4):hover~.nav-box{
  left: calc(100% / 6 *3);
  background-color: #b45252;
}
.nav ul li:nth-child(5):hover~.nav-box{
  left: calc(100% / 6 *4);
  background-color: #b45252;
}
.nav ul li:nth-child(6):hover~.nav-box{
  left: calc(100% / 6 *5);
  background-color: #b45252;
}
</style>
