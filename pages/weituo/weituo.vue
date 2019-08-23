<template>
  <view class="content">
    <view class="top">
      <view class="pic">
        <image src="http://wine-static.yibaicdn.com/de3e0700-c314-11e9-86ad-7336f9e363c2.png" />
        <view class="wen">界仕VIP购买</view>
      </view>
      <view class="bgc">
        <view class="quan">
          <view class="one" v-for="(item, index) in list" :key="index">
            <view>{{item.label}}</view>
            <view class="pay">{{item.value}}</view>
          </view>
          <view class="four">
            <view class="liji">
              <text>立即支付</text>
            </view>
            <view class="agree">
              <text>开通即视为同意</text>
              <text class="xieyi">（界仕会员用户协议）</text>
            </view>
          </view>
        </view>
      </view>
    </view>
    <view class="main">
      <view class="vip">
        <view class="xian"></view>
        <view class="zi">开通界仕VIP 享专属特权</view>
        <image class="bx" src="/tea-test/static/img/路径 17.png" />
      </view>
      <view class="tu">
        <view class="pic1">
          <image src="http://wine-static.yibaicdn.com/de3e0700-c314-11e9-86ad-7336f9e363c2.png" />
        </view>
        <view class="pic1">
          <image src="http://wine-static.yibaicdn.com/de3e0700-c314-11e9-86ad-7336f9e363c2.png" />
        </view>
        <view class="pic1">
          <image src="http://wine-static.yibaicdn.com/de3e0700-c314-11e9-86ad-7336f9e363c2.png" />
        </view>
        <view class="pic1">
          <image src="http://wine-static.yibaicdn.com/de3e0700-c314-11e9-86ad-7336f9e363c2.png" />
        </view>
        <view class="pic1">
          <image src="http://wine-static.yibaicdn.com/de3e0700-c314-11e9-86ad-7336f9e363c2.png" />
        </view>
      </view>
    </view>
  </view>
</template>

<script>
export default {
  data() {
    return {
      list: [
        { label: "购买方式", value: "付费购买" },
        {
          label: "购买期限",
          value: "一年"
        },
        {
          label: "应付金额",
          value: "￥1000"
        }
      ]
    };
  },
  onLoad() {},
  methods: {}
};
</script>
<style lang="less" scoped>
.content {
  width: 100vw;
  height: 220vw;
  background-color: #f9f9f9;
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;

  .top {
    background-image: url("/static/img/背景.png");
    width: 100vw;
    height: 121vw;
    overflow: hidden;
    .pic {
      width: 26vw;
      height: 18vw;
      margin: 5vw auto;
      image {
        width: 21vw;
        height: 17vw;
      }
      .wen {
        color: #ebab08;
        font-size: 4vw;
      }
    }
    .bgc {
      width: 92vw;
      height: 78vw;
      background-color: #fff;
      border-radius: 5px;
      margin: 7vw auto;
      display: flex;
      flex-direction: column;
      align-items: center;
      .quan {
        width: 84vw;
        height: 78vw;
        .one {
          width: 84vw;
          height: 16vw;
          background-color: #fff;
          display: flex;
          align-items: center;
          font-size: 4vw;
          position: relative;

          .pay {
            color: #3059cb;
            font-size: 3vw;
            margin-left: 5vw;
          }
        }
        .one :after {
          content: "";
          position: absolute;
          left: 0;
          bottom: 0;
          width: 84vw;
          height: 1px;
          background-color: #c0c4cc;
        }

        .four {
          width: 84vw;
          height: 30vw;
          background-color: #fff;
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          text-align: center;
          line-height: 12vw;
          .liji {
            width: 60vw;
            height: 12vw;
            background: rgba(48, 89, 203, 1);
            border-radius: 2px;
            color: #fff;
          }
          .agree {
            font-size: 4vw;
            color: #909399;
            .xieyi {
              color: #3059cb;
            }
          }
        }
      }
    }
  }

  // 第二部分
  .main {
    width: 92vw;
    height: 67vw;
    background-color: #fff;
    position: absolute;
    bottom: 37vw;
    border-radius: 1vw;

    .vip {
      width: 68vw;
      height: 23vw;
      display: flex;
      .xian {
        width: 11vw;
        height: 0vw;
        border: 0vw solid;
      }
      .zi {
        width: 46vw;
        height: 6vw;
        font-size: 4vw;
      }
      .bx {
        width: 11vw;
        height: 1vw;
      }
    }
    .tu {
      width: 87vw;
      height: 57vw;
      // border: 1px solid red;
      display: flex;
      flex-wrap: wrap;
      padding-left: 5vw;
      position: absolute;
      bottom: -3vw;
      margin-left: 6vw;
      .pic1 {
        margin-right: 10vw;
        width: 14vw;
        height: 14vw;

        image {
          width: 14vw;
          height: 14vw;
        }
      }
      .pic1:nth-child(3n) {
        margin-right: 0vw;
      }
    }
  }
}
</style>