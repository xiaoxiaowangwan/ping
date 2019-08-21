<template>
  <view class="page">
    <view class="content">
      <view class="content_item">
        <button class="button" type="button" @click="togglePopup('center', 'popup')">中间弹出</button>
      </view>
      <!-- <image src="../../static/icon/fudai.png"></image>  -->
    </view>
    <PopUp ref="popup" :type="type" @change="change">
        <DiyDiv :content="content">
            ...
        </DiyDiv>
    </PopUp>
  </view>
</template>

<script>
import PopUp from "../../components/popup/popup";
import DiyDiv from "../../components/diyDiv/diyDiv";
export default {
  name: "category",
  data() {
    return {
      type: "", // 弹出类型
      show: false, // 是否显示
      content: "" // slot弹出内容
    };
  },
  onLoad() {},
  methods: {
    togglePopup(type, open) {
      switch (type) {
        case "top":
          this.content = "顶部弹出 popup";
          break;
        case "bottom":
          this.content = "底部弹出 popup";
          break;
        case "center":
          this.content = "居中弹出 popup";
          break;
      }
      this.type = type;
      this.$refs[open].open();
    },
    change(e) {
      console.log(e.show);
    }
  },
  components: {
    PopUp,DiyDiv
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
    .content_item {
      padding: 60vw;
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
