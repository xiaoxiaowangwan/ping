<template>
  <view class="content">
    <slot />
    <view class="main">
      <view>
        <image src="###" />
      </view>
    </view>
  </view>
</template>
<script>
export default {};
</script>
<style lang="less" scoped>
.content {
  width: 42.93vw;
  height: 62.53vw;
  border: 1px dashed #000;
  .main {
    background-image: url("/static/img/bgc.png");
    background-size: 38vw 58 w;
  }
}
</style>