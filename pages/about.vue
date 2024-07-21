<template>
  <div>
    关于
    <div @click="navigateTo({ path: '/', query: { data: '我是关于的数据' } })">
      跳转首页
    </div>
  </div>
</template>

<script setup>
const data = useRoute().query.data;
console.log(data);
</script>

<style lang="scss" scoped></style>
