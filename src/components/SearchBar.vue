<script setup lang="ts"></script>

<template>
  <div class="nav-input">
    <input />
  </div>
</template>

<style scoped>
input {
  background-color: transparent;
  border: none;
  margin: 12px /* 36px */;
  color: white;
  font-size: 1.5em;
  /* padding-inline-start: 1em; */
}
input:focus {
  outline: none;
  box-shadow: none;
  border: none;
}

.nav-input {
  width: 500px;
  border-radius: 100px;
  border-color: rgba(255, 255, 255, 0.05);
  border-width: 1px;
  border-style: solid;
  backdrop-filter: blur(32px);
  background-color: rgba(255, 255, 255, 0.1);
  transition-behavior: normal;
  transition-duration: 0.3s;
  transition-timing-function: ease;
  transition-delay: 0s;
  transition-property: all;
}
.nav-input:has(input:focus) {
  border-color: rgba(255, 255, 255, 0.1);
  background-color: rgba(255, 255, 255, 0.2);
}
</style>
