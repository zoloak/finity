<script setup lang="ts">
import { randomRgbColor } from '../util/randomColor'
const color = randomRgbColor()
</script>

<template>
  <div class="shortcut" :style="{ backgroundColor: color }"></div>
</template>

<style scoped>
.shortcut {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  /* background-color: blue; */
}
</style>
