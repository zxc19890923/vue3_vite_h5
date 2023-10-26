<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="success">成功按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
  </div>
  <div>vue3+vite+h5项目配置</div>
</template>
<script setup>
import { showLoadingToast } from 'vant';
showLoadingToast({
  duration: 0,
  forbidClick: true,
  message: '倒计时 3 秒',
});
</script>
<style scoped>
div {
  font-size: 14px;
  text-align: center;
}
</style>
