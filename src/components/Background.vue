<script setup lang="ts"></script>

<template>
  <div id="background-wrapper">
    <div id="background-image"></div>
    <div id="background-filter"></div>
  </div>
</template>

<style scoped>
#background-image {
  z-index: -1;
  position: fixed;
  width: 100%;
  height: 100%;
  background-image: url('@/assets/background/mrfz_1.jpg');
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
#background-filter {
  z-index: -1;
  position: fixed;
  width: 100%;
  height: 100%;
  backdrop-filter: blur(10px);
}
</style>
