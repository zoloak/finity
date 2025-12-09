<script setup lang="ts">
import Background from './components/Background.vue'
import Grid from './components/Grid.vue'
import Shortcut from './components/Shortcut.vue'
</script>

<template>
  <Background />
  <div class="content">
    <Grid>
      <Shortcut></Shortcut>
      <Shortcut></Shortcut>
      <Shortcut></Shortcut>
      <Shortcut></Shortcut>
      <Shortcut></Shortcut>
      <Shortcut></Shortcut>
      <Shortcut></Shortcut>
      <Shortcut></Shortcut>
      <Shortcut></Shortcut>
      <Shortcut></Shortcut>
    </Grid>
  </div>
</template>

<style scoped>
.content {
  display: flex;
  justify-content: center;
}
</style>
