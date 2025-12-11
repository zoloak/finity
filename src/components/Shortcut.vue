<script setup lang="ts">
// import { randomRgbColor } from '../util/randomColor'
// const color = randomRgbColor()
// const color = 'transparent'
</script>

<template>
  <div class="warpper">
    <a href="https://www.bilibili.com/" target="_blank">
      <div class="icon shadow">
        <img class="" src="@/assets/background/mrfz_1.jpg" title="title" />
        <div class="color"></div>
      </div>
    </a>
    <a class="name" href="https://www.bilibili.com/" target="_blank">
      <span class="">bilibili</span>
    </a>
  </div>
</template>

<style scoped>
.warpper {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
}
a {
  cursor: pointer;
  text-decoration: none;
}
.icon {
  width: 120px;
  height: 120px;
  overflow: hidden; /* 裁剪图标 */
  border-radius: 50%;
}
.icon img {
  width: 100%; /* 拉伸 */
  height: 100%; /* 拉伸 */
  display: block; /* 据说是消除行内img元素的边距 */
  object-fit: cover; /* 不知道什么用 */
}
.color {
  background-color: transparent;
}
.name {
  margin-top: 16px;
  color: white;
  font-size: 1rem;
  text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.4);
}
.shadow {
  box-shadow: 10px 5px 10px rgba(0, 0, 0, 0.4);
}
</style>
