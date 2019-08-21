<template>
  <view v-if="showPopup" class="uni-popup">
    <view :class="[ani, animation ? 'ani' : '']" class="uni-popup__mask" @click="close(true)">
     
    </view>
  </view>
</template>

<script>
export default {
  name: "popup",
  data() {
    return {
      ani: "",
      showPopup: false
    };
  },
  props: {
    // 开启动画
    animation: {
      type: Boolean,
      default: true
    },
    // 弹出层类型，可选值，top: 顶部弹出层；bottom：底部弹出层；center：全屏弹出层
    type: {
      type: String,
      default: "center"
    },
    // maskClick
    maskClick: {
      type: Boolean,
      default: true
    },
    show: {
      type: Boolean,
      default: true
    }
  },
  onLoad() {},
  methods: {
    open() {
      this.$emit("change", {
        show: true
      });
      this.showPopup = true;
      this.$nextTick(() => {
        setTimeout(() => {
          this.ani = "uni-" + this.type;
        }, 30);
      });
    },
    close(type) {
      if (!this.maskClick && type) return;
      this.$emit("change", {
        show: false
      });
      this.ani = "";
      this.$nextTick(() => {
        setTimeout(() => {
          this.showPopup = false;
        }, 300);
      });
    }
  }
};
</script>

<style scoped lang="less">
.uni-popup {
  position: fixed;
  top: 0;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 99999;
  overflow: hidden;
  .uni-popup__mask {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    z-index: 998;
    background: rgba(0, 0, 0, 0.4);
    opacity: 0;
  }

  .uni-popup__mask.ani {
    transition: all 0.3s;
  }

  .uni-popup__mask.uni-bottom,
  .uni-popup__mask.uni-center,
  .uni-popup__mask.uni-top {
    opacity: 1;
  }
}
</style>
