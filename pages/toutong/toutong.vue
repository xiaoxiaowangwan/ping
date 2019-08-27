<template>
  <view class="content">
    <view class="one">
      <div class="two">
        <view class="top">
          <view class="img">
            <image src="/static/img/y1.png" />
          </view>

          <text>概述</text>
        </view>
        <view class="main">
          <text>头痛（headache）是指神经系统最常见的症状，是指眉弓以上至枕下部、颈上部范围内的疼痛。引痛、颅内,同…</text>
          <view class="zhan">
            展开
            <view class="jaintou">
              <image src="/static/img/yy.png" class="yy" />
            </view>
          </view>
        </view>
      </div>
    </view>
    <FanY :item="item" v-for="(item,index) in 5" :key="index" />
  </view>
</template>
<script>
import FanY from "../../components/fany/fany";
export default {
  components: {
    FanY
  }
};
</script>
<style lang="less" scoped>
.content {
  width: 100vw;
  height: 178vw;
  background: rgba(246, 246, 248, 1);
  .one {
    width: 100vw;
    height: 38vw;
    background-color: #fff;
    display: flex;
    justify-content: center;
    .two {
      width: 93.07vw;
      height: 38vw;

      .top {
        width: 93.07vw;
        height: 12.67vw;
        display: flex;
        align-items: flex-end;
        .img {
          width: 7vw;
          height: 7vw;
          border: 1px dashed #000;
          image {
            width: 7vw;
            height: 7vw;
          }
        }
        text {
          padding-left: 1vw;
          width: 9vw;
          height: 6vw;
          font-size: 4vw;
          font-family: PingFangSC;
          font-weight: 700;
          color: rgba(48, 49, 51, 1);
        }
      }
      .main {
        width: 93vw;
        height: 23vw;
        display: flex;
        align-items: flex-end;
        margin-top: 2.67vw;
        flex-direction: column;
        text-align: justify;
        position: relative;
        text {
          font-size: 5vw;
          font-family: PingFangSC;
          font-weight: 400;
          color: rgba(96, 98, 102, 1);
        }
        .zhan {
          color: #2d8cfc;
          display: flex;
          flex-direction: row;
          align-items: center;
          position: absolute;
          top: 14vw;
          right: 0vw;
          margin-left: 2vw;
          .jaintou {
            width: 7vw;
            height: 4vw;
            border: 1px dashed #000;
            margin-left: 2vw;
            .yy {
              width: 7vw;
              height: 4vw;
              vertical-align: text-top;
            }
          }
        }
      }
    }
  }
}
</style>