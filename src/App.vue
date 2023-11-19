<script setup>
import MaioPageView from './views/MiaoPageView.vue';
</script>

<template>
  <MaioPageView />
</template>

<style lang="scss">
@font-face {
  font-family: 'Inter';
  src: url('../src/assets/style/font/inter/Inter-Regular.ttf')
    format('truetype');
  font-weight: 400;
  font-style: normal;
}

body {
  font-family: noto-sans-tc, Inter, sans-serif;
}
</style>
