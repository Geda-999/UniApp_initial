<template>
  <view>
    <view class="text">hello 面前的你是不是在想我呀！</view>
    <!-- 下部导航栏 -->
    <tab-bar></tab-bar>
  </view>
</template>

<script>
import tabBar from "@/components/tabBar.vue";
export default {
  components: {
    tabBar,
  },
};
</script>

<style lang="scss">
.text {
  font-size: 20px;
  color: rgb(255, 0, 106);
}
</style>
