<template>
  <div class="home">
    首页
    <!-- <Banner />
    <BannerChild /> -->
    <nuxt-link to="/about?data='我是首⻚的数据'">跳转去关于我们页面</nuxt-link>
  </div>
</template>

<script setup>
const data = useRoute().query.data;
console.log(data);
</script>

<style scoped>
.home {
  background-color: aqua;
}
</style>
