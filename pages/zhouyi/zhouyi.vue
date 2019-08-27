<template>
  <view class="content">
    <view class="sou">
      <input />
      <view class="suo">
        <image src="/static/img/sou.png" class="img" />
        <text>搜索</text>
      </view>
    </view>
    <view class="main">
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

      <message :item="item" v-for="(item, index) in 6" :key="index" />
    </view>
  </view>
</template>
<script>
import message from "../../components/message/message";
export default {
  data() {
    return {};
  },
  components: {
    message
  }
};
</script>
<style lang="less" scoped>
.content {
  width: 100vw;
  height: 161vw;
  background-color: #fff;
  .sou {
    width: 100vw;
    height: 15vw;
    background-color: #f6f6f8;
    position: relative;
    input {
      width: 93vw;
      height: 9vw;
      background-color: #fff;
      border-radius: 4.5vw;
      margin-left: 4vw;
    }
    .suo {
      width: 18vw;
      height: 5vw;
      display: flex;
      position: absolute;
      top: 2vw;
      left: 42vw;
      .img {
        width: 5vw;
        height: 5vw;
        border: 1px dashed #000;
      }
      text {
        font-size: 4vw;
        font-family: PingFangSC;
        font-weight: 500;
        color: rgba(192, 196, 204, 1);
        padding-left: 2vw;
      }
    }
  }
  .main {
    width: 100vw;
    height: 146vw;
    background-clip: #fff;
    .one {
      width: 98vw;
      height: 12.27vw;
      margin-top: 6.8vw;
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
  }
}
</style>