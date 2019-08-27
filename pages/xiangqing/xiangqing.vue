<template>
  <view class="content">
    <view class="top">
      <view class="one">1. Online shopping environments</view>
      <view class="two">标签</view>
      <view
        class="three"
      >A unique characteristic of online shopping environments is that they allow vendors to create retail interfaces with highly interactive features. One desirable form of interactivity from a consumer perspective is the implementation of sophisticated tools to assist shoppers in their purchase decisions by customizing the electronic shopping environment to their individual preferences.</view>
      <button class="btn">
        <view class="hua"></view>
        <text>暂无录音</text>
      </button>
    </view>
    <view class="footer">
      <view class="bao">
        <view class="title">
          <view class="lian">参与讨论</view>
          <view class="xi">优秀练习</view>
          <view class="xi">我的练习</view>
        </view>
        <view class="tijiao">
          <view>
            <text>已提交:</text>
            <text class="er">2人</text>
          </view>
          <view class="moren">
            <text class="shai">默认筛选</text>
            <view class="img">
              <image src="/static/img/xiajiant.png" />
            </view>
          </view>
        </view>
        <view class="yonghu">
          <view class="kuang">
            <image src="/static/img/nvde.png" class="tu" />
          </view>
          <view class="zong">
            <view class="name">
              <text class="mingc">用户名称</text>
              <image src="/static/img/jinxuan.png" class="jinxuan" />
            </view>
            <text class="time">三天前</text>
          </view>
          <view class="hui">
            <image src="/static/img/huihua.png" class="hua" />
          </view>
          <view class="zan">
            <image src="/static/img/dianzan.png" class="dian" />
            <text>0</text>
          </view>
        </view>
        <view class="drtion">
          <view class="kouyu">口语从29到90,这个PTE⑧炸经验帖我跪着看完了</view>
          <view class="huat">
            <div class="zuo">
              <image src="/static/img/zuo.png" class="zzuo" />
            </div>
            <view class="center">
              <image src="/static/img/ting.png" class="ccenter" />
              <text>按住录音</text>
            </view>
            <view class="right">
              <image src="/static/img/you.png" class="yyou" />
            </view>
          </view>
          <view class="xian"></view>
        </view>
      </view>
    </view>
  </view>
</template>
<script>
export default {};
</script>
<style lang="less" scoped>
.content {
  width: 100vw;
  height: 216.53vw;
  background-color: #f5f7fa;
  .top {
    width: 100vw;
    height: 90vw;
    background-color: #fff;
    padding-left: 4vw;
    .one {
      font-size: 4vw;
      font-family: PingFangSC;
      font-weight: 600;
      color: rgba(21, 28, 90, 1);
    }
    .two {
      width: 10.67vw;
      height: 4.53vw;
      background-image: url("/static/img/xiang.png");
      background-size: 10.67vw 4.53vw;
      border: 1px dashed #000;
      margin-top: 1.33vw;
      font-size: 3vw;
      font-family: PingFangSC;
      font-weight: 400;
      color: rgba(21, 28, 90, 1);
      text-align: center;
    }
    .three {
      font-size: 4vw;
      font-family: PingFangSC;
      font-weight: 400;
      color: rgba(24, 27, 71, 1);
      margin-top: 4vw;
      text-align: justify;
      width: 90vw;
    }
    .btn {
      width: 48vw;
      height: 13vw;
      background: rgba(245, 247, 250, 1);
      border-radius: 6vw;
      position: relative;
      margin: 5.33vw auto;
      .hua {
        width: 6.4vw;
        height: 6.4vw;
        background-image: url("/static/img/huatong.png");
        background-size: 4.27vw 6.13vw;
        background-repeat: no-repeat;
        border: 1px dashed #000;
        background-position: 1vw 0vw;
        position: absolute;
        top: 3vw;
        left: 10.67vw;
      }
      text {
        font-size: 4vw;
        font-family: PingFangSC;
        font-weight: 500;
        color: rgba(192, 196, 204, 1);
        padding-left: 8.67vw;
      }
    }
  }
  .footer {
    width: 100vw;
    height: 93.07vw;
    background-color: #fff;
    margin-top: 2.67vw;
    .bao {
      width: 92vw;
      height: 93.07vw;
      display: flex;
      flex-direction: column;
      align-items: center;
      background-color: #fff;
      margin: auto;
      .title {
        width: 100vw;
        height: 8vw;
        display: flex;
        justify-content: space-evenly;
        align-items: flex-end;
        .lian {
          font-size: 3vw;
          font-family: PingFangSC;
          font-weight: 600;
          color: rgba(21, 28, 90, 1);
        }
        .xi {
          font-size: 3vw;
          font-family: PingFangSC;
          font-weight: 600;
          color: rgba(144, 147, 153, 1);
        }
      }
      .tijiao {
        font-size: 3vw;
        font-family: PingFangSC;
        font-weight: 400;
        color: rgba(144, 147, 153, 1);
        display: flex;
        justify-content: space-between;
        width: 93vw;
        margin-top: 7.2vw;
        .er {
          padding-left: 2vw;
        }
        .moren {
          display: flex;
          .shai {
            margin-right: 0.8vw;
          }
          .img {
            width: 4vw;
            height: 4vw;
            border: 0.5vw dashed #000;

            image {
              width: 3vw;
              height: 3vw;
              padding-left: 0.5vw;
            }
          }
        }
      }
      .yonghu {
        width: 92vw;
        height: 8vw;
        background-color: #fff;
        display: flex;
        position: relative;
        margin-top: 6vw;
        .kuang {
          width: 8vw;
          height: 8vw;
          border: 1px dashed #000;
          .tu {
            width: 8vw;
            height: 8vw;
            border-radius: 50%;
          }
        }
        .zong {
          width: 21.63vw;
          height: 8.26vw;
          display: flex;
          flex-direction: column;
          padding-left: 2.53vw;
          position: relative;
          .name {
            width: 23.63vw;
            height: 4.53vw;
            display: flex;
            .mingc {
              font-size: 3vw;
              font-family: PingFangSC;
              font-weight: 500;
              color: rgba(144, 147, 153, 1);
            }
            .jinxuan {
              width: 8vw;
              height: 3.47vw;
              border: 1px dashed #000;
              margin-left: 1.33vw;
            }
          }
          .time {
            font-size: 2vw;
            font-family: PingFangSC;
            font-weight: 400;
            color: rgba(192, 196, 204, 1);
          }
        }
        .hui {
          width: 4.5vw;
          height: 4.5vw;

          position: absolute;
          top: 3px;
          right: 63px;
        }
        .hua {
          width: 4vw;
          height: 4vw;
          border: 1px dashed #000;
        }
        .zan {
          width: 4.5vw;
          height: 4.5vw;
          position: absolute;
          top: 1vw;
          right: 7vw;
          .dian {
            width: 4vw;
            height: 4vw;
            border: 1px dashed #000;
          }
          text {
            font-size: 2vw;
            color: rgba(192, 196, 204, 1);
            position: absolute;
            top: 1vw;
            right: -4vw;
          }
        }
      }
      .drtion {
        width: 93vw;
        height: 62vw;
        margin-top: 2vw;
        position: relative;
        .kouyu {
          font-size: 4vw;
          font-family: PingFangSC;
          font-weight: 400;
          color: rgba(21, 28, 90, 1);
          display: flex;
          flex-direction: column;
          align-items: center;
        }
        .huat {
          width: 93vw;
          height: 24vw;
          display: flex;
          justify-content: space-around;
          align-items: baseline;
          margin-top: 17vw;
          .zuo {
            width: 6.4vw;
            height: 6.4vw;
            border: 1px dashed #000;
            text-align: center;
            .zzuo {
              width: 3vw;
              height: 3vw;
            }
          }
          .center {
            width: 23vw;
            height: 23vw;
            border: 1px dashed #000;
            text-align: center;
            text {
              font-size: 4vw;
              font-family: PingFangSC;
              font-weight: 500;
              color: rgba(192, 196, 204, 1);
            }
            .ccenter {
              width: 23vw;
              height: 23vw;
            }
          }
          .right {
            width: 6.4vw;
            height: 6.4vw;
            border: 1px dashed #000;
            text-align: center;
            .yyou {
              width: 3vw;
              height: 3vw;
            }
          }
        }
        .xian {
          width: 36vw;
          height: 1vw;
          background: rgba(0, 0, 0, 1);
          border-radius: 27px;
          position: absolute;
          bottom: 2vw;
          left: 28vw;
        }
      }
    }
  }
}
</style>