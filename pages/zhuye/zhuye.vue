<template>
  <view class="content">
    <Top />
    <view class="main"></view>
    <view class="number"></view>
    <view class="introduce"></view>
    <view class="case"></view>
    <view class="grade"></view>
    <view class="evaluate"></view>
  </view>
</template>
<script>
import Top from "../../components/top/top";
export default {
  components: {
    Top
  }
};
</script>
<style lang="less" scoped>
.content {
  width: 100vw;
  height: 388.27vw;
  background-color: #f4f6fb;
}
</style>