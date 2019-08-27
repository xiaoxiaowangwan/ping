<template>
  <view class="content">
    <KeCheng :item="item" v-for="(item, index) in 6" :key="index" />
  </view>
</template>
<script>
import KeCheng from "../../components/kecheng/kecheng";
export default {
  components: {
    KeCheng
  }
};
</script>
<style lang="less" scoped>
.content {
  width: 100vw;
  height: 216.53vw;
  background-color: #fff;
}
</style>