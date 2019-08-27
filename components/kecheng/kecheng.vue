<template>
  <view class="top">
    <view class="left">
      <image class="one" src="/static/img/xxx.png" />
    </view>
    <view class="right">
      <view class="eng">英语零基础到口语达人全入…</view>
      <view class="time">时长：12:00</view>
      <view class="bt">
        <view class="kuang">
          <image src="/static/img/yuan.png" class="two" />
        </view>

        <view class="cc">陈超</view>
        <view class="price">¥699.00</view>
      </view>
    </view>
  </view>
</template>
<script>
export default {
  props: {
    type: Array
  }
};
</script>

<style lang="less" scoped>
.top {
  width: 100vw;
  height: 46vw;
  display: flex;

  .left {
    width: 50vw;
    height: 46vw;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    .one {
      width: 44vw;
      height: 32.8vw;
      opacity: 1;
    }
  }
  .right {
    width: 50vw;
    height: 46vw;
    display: flex;
    flex-direction: column;

    padding-left: 2.4vw;
    .eng {
      width: 44vw;
      height: 11vw;
      font-size: 4vw;
      font-family: PingFangSC;
      font-weight: 700;
      color: rgba(21, 28, 90, 1);
      margin-top: 7.73vw;
    }
    .time {
      width: 18vw;
      height: 5vw;
      font-size: 3vw;
      font-family: PingFangSC;
      font-weight: 500;
      color: rgba(220, 223, 230, 1);
      margin-top: 1.13vw;
    }
    .bt {
      display: flex;
      align-items: center;
      margin-top: 8vw;
      .kuang {
        width: 5.33vw;
        height: 5.33vw;
        border: 1px dashed #000;
        .two {
          width: 5.33vw;
          height: 5.33vw;
          border-radius: 50%;
        }
      }
      .cc {
        width: 8vw;
        height: 5vw;
        font-size: 3vw;
        font-family: PingFangSC;
        font-weight: 400;
        color: rgba(144, 147, 153, 1);
        margin-left: 1.87vw;
      }
      .price {
        width: 16vw;
        height: 5vw;
        font-size: 4vw;
        font-family: PingFangSC;
        font-weight: 600;
        color: rgba(224, 32, 32, 1);
        margin-left: 14.13vw;
      }
    }
  }
}
</style>