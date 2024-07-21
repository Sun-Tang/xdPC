<template>
  <div>
    关于
    <div @click="navigateTo('/')">跳转首页</div>
  </div>
</template>

<script setup>
import { navigateTo } from 'nuxt/dist/app/composables/router';
</script>

<style lang="scss" scoped></style>
