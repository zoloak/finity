<script setup lang="ts">
import Background from './components/Background.vue'
import Grid from './components/Grid.vue'
import SearchBar from './components/SearchBar.vue'
import Shortcut from './components/Shortcut.vue'
</script>

<template>
  <Background />
  <div class="content">
    <SearchBar />
    <Grid style="margin-top: 48px">
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
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
