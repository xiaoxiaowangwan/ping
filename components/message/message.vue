<template>
  <view class="one">
    <view class="left">
      <image src="/static/img/share.png" class="tu" />
    </view>
    <view class="center">
      <view class="te">共享账号</view>
      <view class="xt">您可以共享自己及创建子账号给通讯录亲人</view>
    </view>
    <view class="right">
      <image src="/static/img/youjian.png" class="jian" />
    </view>
  </view>
</template>
<script>
export default {
  data() {
    return {};
  }
};
</script>
<style lang="less" scoped>
.one {
  width: 98vw;
  height: 12.27vw;
  margin-top: 2.67vw;
  display: flex;
  justify-content: space-around;
  align-items: center;

  .left {
    width: 12vw;
    height: 12.27vw;
    border: 1px dashed #000;
    .tu {
      width: 12vw;
      height: 12.27vw;
    }
  }
  .center {
    width: 65.87vw;
    height: 12.27vw;
    .te {
      font-size: 5vw;
      font-family: PingFangSC;
      font-weight: 500;
      color: rgba(94, 103, 132, 1);
    }
    .xt {
      font-size: 3vw;
      font-family: PingFangSC;
      font-weight: 400;
      color: rgba(144, 147, 153, 1);
    }
  }
  .right {
    width: 5.87vw;
    height: 5.87vw;
    border: 1px dashed #000;
    text-align: center;

    .jian {
      width: 3.87vw;
      height: 3.87vw;
    }
  }
}
</style>