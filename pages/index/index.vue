<template>
  <view class="content">
    <view class="nav">
      <view class="picture"></view>
      <view class="ziliao">
        <view class="pic"></view>
        <view class="gxlz">
          <text>哈哈哈</text>
          <text>广西柳州|民事诉讼</text>
        </view>
        <view class="time">
          <text>3小时前</text>
        </view>
      </view>
      <view class="pay">
        <text>合伙人把资金花完了怎么办？</text>
        <view>></view>
      </view>
    </view>
    <view class="main">
      <view class="pingtai">
        <view class="yuan">
          <view class="xin"></view>
        </view>
        <view class="zi">界式律师平台</view>
      </view>
      <view class="look">
        <view class="xuni">虚拟协议文本</view>
        <view class="chak">
          <view class="jujue">拒绝</view>
          <view class="kan">查看</view>
        </view>
      </view>
      <view class="price">
        <view>服务价格</view>
        <view>￥3000</view>
      </view>
    </view>
    <view class="dingd">
      <view>订单编号:123456788901203</view>
      <view>下单时间:2019-3-2 23:12:13</view>
    </view>
    <view class="footer">
      <view class="jiage">
        <view>￥</view>
        <view class="da">3000</view>
      </view>
      <view class="argee">
        <text>同意并支付</text>
      </view>
    </view>
  </view>
</template>

<script>
export default {
  data() {
    return {};
  },
  onLoad() {},
  methods: {}
};
</script>
<style scoped lang="less">
.content {
  width: 100vw;
  height: 190vw;
  background-color: #f6f6f6;
  display: flex;
  flex-direction: column;
  .nav {
    display: flex;
    flex-direction: column;
    .picture {
      width: 100vw;
      height: 30vw;
      background-color: orange;
    }
    .ziliao {
      width: 100vw;
      height: 20vw;
      background-color: pink;
      display: flex;
      justify-content: space-between;
      padding-right: 2vw;
      .pic {
        width: 10vw;
        height: 10vw;
        border-radius: 5vw;
        background-color: yellow;
        margin-left: 2vw;
        margin-left: 6vw;
        margin-top: 5vw;
      }
      .gxlz {
        width: 60vw;
        height: 20vw;
        background-color: green;
        display: flex;
        flex-direction: column;
      }
    }
    .pay {
      width: 100vw;
      height: 10vw;
      background-color: skyblue;
      display: flex;
      justify-content: space-between;
      padding-left: 2vw;
      padding-right: 2vw;
      align-items: center;
    }
  }
  //   main部分
  .main {
    display: flex;
    flex-direction: column;
    margin-top: 10vw;
    .pingtai {
      width: 100vw;
      height: 30vw;
      background-color: orange;
      display: flex;
      //   justify-content: center;
      //   align-items: center;
      .yuan {
        width: 30vw;
        height: 30vw;
        background-color: skyblue;
        display: flex;
        justify-content: center;
        align-items: center;
        .xin {
          width: 10vw;
          height: 10vw;
          background-color: pink;
          border-radius: 5vw;
          margin-left: -10vw;
        }
      }
      .zi {
        width: 60vw;
        height: 30vw;
        background-color: green;
        line-height: 30vw;
        margin-left: -12vw;
      }
    }
    .look {
      width: 100vw;
      height: 20vw;
      background-color: pink;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      .xuni {
        width: 30vw;
        // height: 20vw;
      }
      .chak {
        width: 30vw;
        display: flex;
        align-self: flex-end;
        justify-content: space-around;
      }
    }
    .price {
      width: 100vw;
      height: 10vw;
      background-color: skyblue;
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      align-items: center;
      padding-left: 2vw;
      padding-right: 2vw;
    }
  }
  .dingd {
    padding-left: 2vw;
    padding-top: 2vw;
  }
  // footer部分
  .footer {
    width: 100vw;
    height: 20vw;
    display: flex;
    background-color: hotpink;
    margin-top: 20vw;
    justify-content: space-between;
    .jiage {
      width: 30vw;
      height: 20vw;
      background-color: yellow;
      display: flex;
      justify-content: center;
      align-items: baseline;
      line-height: 20vw;
      .da {
        font-size: 7vw;
      }
    }
    .argee {
      width: 30vw;
      height: 20vw;
      background-color: yellow;
      text-align: center;
      line-height: 20vw;
    }
  }
}
</style>





