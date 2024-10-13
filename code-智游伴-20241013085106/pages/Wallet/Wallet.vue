<template>
  <view class="flex-col page">
    <view class="flex-row justify-between items-center">
      <text class="text">Wallet</text>
      <image
        class="image"
        src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=9a5141fc06960302b6207fca4b661357.png"
      />
    </view>
    <image
      class="mt-24 image_2"
      src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=0b5d1a7645aba9daa65cbe2846ceae50.png"
    />
  </view>
</template>

<script>
  export default {
    components: {},
    props: {},
    data() {
      return {};
    },

    methods: {},
  };
</script>

<style scoped lang="css">
  .page {
    padding: 204.2rpx 30.53rpx 885.5rpx;
    background-color: #f2f2f7;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
    height: 100%;
  }
  .text {
    color: #000000;
    font-size: 64.89rpx;
    font-family: SF Pro Display;
    font-weight: 700;
    line-height: 46.41rpx;
  }
  .image {
    width: 154.58rpx;
    height: 62.98rpx;
  }
  .image_2 {
    margin-right: 5.73rpx;
    border-radius: 20.99rpx;
    width: 91.0941vw;
    height: 56.9975vw;
  }
</style>