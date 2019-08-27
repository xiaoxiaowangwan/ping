<template>
  <view class="main">
    <view class="top">
      <image src="/static/img/律师头像@2x(1).png" />
      <view class="li">
        <text>李律师</text>
      </view>
      <view class="right">
        <view class="wanc">
          <text>已完成</text>
        </view>
        <view class="fu">
          <text>></text>
        </view>
      </view>
    </view>
    <view class="bottom">
      <div class="time"></div>
    </view>
  </view>
</template>
<style lang="less" scoped>
.main {
  width: 95vw;
  height: 36vw;
  background-color: #fff;
  .top {
    height: 12vw;
    background-color: pink;
    display: flex;
    padding-top: 3vw;
    align-items: center;
    justify-content: space-between;
    margin-top: 5vw;
    image {
      width: 9vw;
      height: 9vw;
      background-color: skyblue;
      border-radius: 50%;
      margin-left: 3vw;
    }
    .li {
      padding-left: 3vw;
      width: 10vw;
      height: 5vw;
      font-size: 3vw;
      font-family: PingFangSC;
      font-weight: 400;
      color: rgba(96, 98, 102, 1);
      margin-left: -56vw;
    }
    .right {
      width: 15vw;
      height: 5vw;
      display: flex;

      .wanc {
        width: 10vw;
        height: 5vw;
        font-size: 3vw;
        font-family: PingFangSC;
        font-weight: 400;
        color: rgba(144, 147, 153, 1);
      }
      .fu {
        width: 2vw;
        height: 5vw;
        color: rgba(163, 163, 163, 1);
      }
    }
  }
  .bottom {
    height: 19vw;
    background-color: skyblue;
    display: flex;
    flex-direction: column;
  }
}
</style>
