<template>
  <view class="content">
    <WancLvshi />
  </view>
</template>
<style lang="less" scoped>
.content {
  background-color: #f9f9f9;
  width: 100vw;
  height: 220vw;
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
<script>
import WancLvshi from "../../components/wanclvshi/wanclvshi";
export default {
  components: {
    WancLvshi
  }
};
</script>
