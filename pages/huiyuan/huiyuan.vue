<template>
  <view class="content">
    <view class="top">
      <view class="one">
        <view class="day">7天会员</view>
      </view>
      <view class="two">
        <view class="month">连续包月</view>
      </view>
      <view class="three">
        <view class="cart">月卡</view>
      </view>
    </view>
    <view class="main">
      <view class="first" :item="item" v-for="(item, index) in 16" :key="index">
        <image src="/static/img/im1.png" />
      </view>
    </view>
    <view class="footer">
      <view class="dui">
        <view class="yuan"></view>
        <text>我已同意《PanDa PTE 会员协议》</text>
      </view>
      <view class="agree">开通会员</view>
    </view>
  </view>
</template>
<script>
export default {
  data() {
    return {
      form: {
        hello: "/static/img/img2.png"
      }
    };
  }
};
</script>
<style lang="less" scoped>
.content {
  width: 100vw;
  height: 216.53vw;
  background: rgba(255, 255, 255, 1);
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;
  .top {
    width: 100vw;
    height: 36vw;
    background: linear-gradient(
      224deg,
      rgba(150, 155, 196, 1) 0%,
      rgba(93, 98, 146, 1) 100%
    );
    display: flex;
    justify-content: space-between;

    .one {
      width: 32.8vw;
      height: 40.53vw;
      //   border: 1px dashed #a2583f;
      background-size: 24.27vw 32vw;
      background-image: url("/static/img/lan.png");
      background-repeat: no-repeat;
      background-position: 6vw 15vw;
      position: relative;
      .day {
        font-size: 4vw;
        font-family: PingFangSC;
        font-weight: 600;
        color: rgba(70, 70, 70, 1);
        position: absolute;
        top: 20vw;
        left: 11vw;
      }
    }
    .two {
      width: 32.8vw;
      height: 40.53vw;
      //   border: 1px dashed #a2583f;
      background-size: 24.27vw 32vw;
      background-image: url("/static/img/hu.png");
      background-repeat: no-repeat;
      background-position: 6vw 15vw;
      position: relative;
      .month {
        font-size: 4px;
        font-family: PingFangSC;
        font-weight: 600;
        color: rgba(131, 89, 35, 1);
        position: absolute;
        top: 20vw;
        left: 11vw;
      }
    }

    .three {
      width: 32.8vw;
      height: 40.53vw;
      border: 1px dashed #a2583f;
      background-size: 24.27vw 32vw;
      background-image: url("/static/img/ho.png");
      background-repeat: no-repeat;
      background-position: 6vw 15vw;
      position: relative;
      .cart {
        font-size: 4px;
        font-family: PingFangSC;
        font-weight: 600;
        color: rgba(131, 89, 35, 1);
        position: absolute;
        top: 20vw;
        left: 14vw;
      }
    }
  }
  .main {
    width: 100vw;
    height: 100vw;
    background-color: #fff;
    margin-top: 16.27vw;
    display: flex;
    flex-wrap: wrap;
    align-content: space-evenly;
    padding-left: 5.6vw;
    position: absolute;
    top: 20vw;
    margin-left: 4vw;
    .first {
      width: 13.13vw;
      height: 13.13vw;
      border: 1px dashed #000;
      margin-right: 10.73vw;
      image {
        width: 13.13vw;
        height: 13.13vw;
      }
    }
  }
  .footer {
    height: 26vw;
    width: 84vw;
    position: absolute;
    top: 131vw;

    .dui {
      display: flex;
      margin-top: 10vw;
      margin-left: 2vw;
      .yuan {
        width: 4vw;
        height: 4vw;
        background-color: #5d6292;
        border-radius: 50%;
      }
      text {
        font-size: 3vw;
        font-family: Helvetica;
        color: rgba(91, 159, 255, 1);
        padding-left: 2vw;
      }
    }
    .agree {
      width: 84vw;
      height: 13vw;
      border-radius: 7.5vw;
      background-image: url("/static/img/huiyuan.png");
      background-size: 84vw 13vw;
      text-align: center;
      line-height: 13vw;
      font-size: 5vw;
      font-family: PingFangSC;
      font-weight: 600;
      color: rgba(131, 89, 35, 1);
      margin-top: 4vw;
    }
  }
}
</style>