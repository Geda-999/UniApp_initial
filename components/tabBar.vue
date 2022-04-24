<template>
  <view>
    <!-- 下部导航栏 -->
    <u-tabbar v-model="current" :list="list"></u-tabbar>
  </view>
</template>

<script>
export default {
  data() {
    return {
      list: [
        {
          iconPath: "home",
          selectedIconPath: "home-fill",
          text: "首页",
          customIcon: false,
          pagePath: "/pages/index/index",
        },
        {
          iconPath: "account",
          selectedIconPath: "account-fill",
          text: "我的",
          customIcon: false,
          pagePath: "/pages/test/test",
        },
      ],
      current: 0,
    };
  },
};
</script>

<style></style>
