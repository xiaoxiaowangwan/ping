<template>
  <view class="content">
    <view class="header">
      <view class="top">
        <view class="tleft">
          <view class="pic"></view>
        </view>
        <view class="center">
          <view class="shang">
            <view class="big">马云</view>
            <view class="small">2019/8/22</view>
          </view>
          <view class="xia">李律师很好，很专业</view>
        </view>
      </view>
      <div class="comment">
        <view class="xia">
          <view class="tu"></view>
          <view class="wen">
            <text>李律师</text>
          </view>
        </view>
      </div>
    </view>
    <view class="header">
      <view class="top">
        <view class="tleft">
          <view class="pic"></view>
        </view>
        <view class="center">
          <view class="shang">
            <view class="big">马云</view>
            <view class="small">2019/8/22</view>
          </view>
          <view class="xia">李律师很好，很专业</view>
        </view>
      </view>
      <div class="comment">
        <view class="xia">
          <view class="tu"></view>
          <view class="wen">
            <text>李律师</text>
          </view>
        </view>
      </div>
    </view>
  </view>
</template>
<style lang="less" scoped>
.content {
  width: 100vw;
  height: 180vw;
  display: flex;
  flex-direction: column;
  .header {
    width: 100vw;
    height: 40vw;
    background-color: pink;
    margin-top: 10vw;
    .top {
      width: 100vw;
      height: 20vw;
      background-color: skyblue;
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      .tleft {
        width: 20vw;
        height: 20vw;
        display: flex;
        justify-content: center;
        align-items: center;

        .pic {
          width: 15vw;
          height: 15vw;
          border-radius: 7.5vw;
          background-color: red;
        }
      }
      .center {
        width: 80vw;
        font-size: 5vw;
        display: flex;
        // flex-direction: row;
        // justify-content: center;
        // width: 80vw;
        // justify-content: flex-start;
        flex-direction: column;
        margin-right: 34vw;
        .shang {
          display: flex;
          justify-content: space-between;
          color: #fff;
          margin-top: 2vw;
          .small {
            font-size: 3vw;
            margin-right: 6vw;
          }
        }
      }
    }
    .comment {
      width: 100vw;
      height: 20vw;
      background-color: yellow;
      display: flex;
      justify-content: flex-end;
      align-items: center;
      .xia {
        width: 70vw;
        height: 15vw;
        background-color: #fff;
        margin-right: 4vw;
        display: flex;
        .tu {
          width: 15vw;
          height: 15vw;
          border-radius: 7.5vw;
          background-color: pink;
        }
        .wen {
          margin-top: 2vw;
          margin-left: 2vw;
        }
      }
    }
  }
  .main {
    width: 100vw;
    height: 40vw;
    background-color: skyblue;
    margin-top: 10vw;
  }
}
</style>