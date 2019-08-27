<template>
  <view class="content">
    <view class="header">
      <view class="liwu">
        <image src="/tea-test/static/img/礼物 活动@2x.png" />
        <view class="pre">已选礼物</view>
      </view>
      <view class="zx">
        <view class="img"></view>
        <view class="wenzi">
          <view>莫高红酒2支装长相守冰红冰白葡萄酒</view>
          <view>冰酒白葡萄酒500ml*2送香槟杯</view>
        </view>
      </view>
    </view>
    <view class="main">
      <view class="xie">
        <image src="/tea-test/static/img/编辑@2x.png" />
        <view class="zhufu">写点祝福</view>
      </view>
      <view class="txt">
        <textarea placeholder="小小心意，愿你欢喜~" class="wenben" v-model="form.hello"></textarea>
      </view>
    </view>
    <button class="footer" @click="goto">
      <text>赠送好友</text>
    </button>
  </view>
</template>
<style lang="less" scoped>
.content {
  width: 100vw;
  height: 161vw;
  display: flex;
  flex-direction: column;
  background-color: #ececec;
  .header {
    width: 100vw;
    height: 67vw;
    background-color: #fff;

    .liwu {
      width: 100vw;
      height: 10vw;
      display: flex;
      padding-left: 4vw;
      padding-top: 4vw;
      image {
        width: 6vw;
        height: 6vw;
      }
      .pre {
        font-size: 4vw;
        color: #333333;
        margin-left: 2vw;
        font-family: PingFangSC;
        font-weight: 500;
      }
    }
    .zx {
      width: 100vw;
      height: 57vw;
      display: flex;
      flex-direction: column;
      align-items: center;
      .img {
        width: 35vw;
        height: 35vw;
        background-color: blue;
      }
      .wenzi {
        margin-top: 3vw;
        display: flex;
        flex-direction: column;
        align-items: center;
        font-size: 4vw;
        font-family: PingFangSC;
        font-weight: 400;
      }
    }
  }
  .main {
    width: 100vw;
    height: 67vw;
    background-color: #fff;
    margin-top: 3vw;
    .xie {
      width: 100vw;
      height: 10vw;
      display: flex;
      padding-left: 4vw;
      padding-top: 4vw;
      image {
        width: 6vw;
        height: 6vw;
      }
      .zhufu {
        font-size: 4vw;
        color: #333333;
        margin-left: 2vw;
        font-family: PingFangSC;
        font-weight: 500;
      }
    }
    .txt {
      width: 75vw;
      height: 38vw;
      background-color: #fff;
      margin: auto;
      border: 1px solid #ececec;
      .wenben {
        padding-top: 3vw;
        padding-left: 3vw;
      }
    }
  }
  .footer {
    width: 75vw;
    height: 12vw;
    background-color: #d7322b;
    margin: 8vw auto;
    font-size: 4vw;
    color: #fff;
    text-align: center;
    line-height: 12vw;
  }
}
</style>
<script>
export default {
  data() {
    return {
      form: {
        hello: "小小心意，愿你欢喜~"
      }
    };
  },
  methods: {
    goto() {
      this.$router.push("/pages/lushi/lushi.vue");
    }
  }
};
</script>