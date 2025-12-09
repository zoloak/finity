<script setup lang="ts"></script>

<template>
  <div class="grid">
    <slot></slot>
  </div>
</template>

<style scoped>
.grid {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  column-gap: 16px;
  row-gap: 16px;
}
</style>
