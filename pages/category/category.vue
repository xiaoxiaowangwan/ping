<template>
  <view class="page">
    <view class="content">
      <view class="example-body">
        <button class="button" type="button">中间弹出 popup</button>
      </view>
      <!-- <image src="../../static/icon/fudai.png"></image>  -->
    </view>
    <PopUp></PopUp>
  </view>
</template>

<script>
import PopUp from "../../components/popup/popup";
export default {
  name: "category",
  data() {
    return {
      title: "Hello"
    };
  },
  onLoad() {},
  methods: {},
  components: {
    PopUp
  }
};
</script>

<style scoped lang="less">
.page {
  width: 100%;
  height: 100%;
  .content {
    display: flex;
    align-items: center;
    justify-content: center;
    .example-body {
    //   border-top: 1vw #f5f5f5 solid;
      padding: 60vw;
    //   background: #fff;
    }
    > image {
      width: 80vw;
      height: 101vw;
      background: rgba(201, 73, 72, 1);
      border-radius: 1vw;
      margin-top: 20vw;
    }
  }
}
</style>
