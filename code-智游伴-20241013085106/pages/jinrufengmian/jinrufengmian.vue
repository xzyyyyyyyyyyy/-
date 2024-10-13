<template>
  <view class="flex-col page">
    <image
      class="image"
      src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=3fd7d085c3cd923c813d4bb5f05d130c.png"
    />
    <view class="flex-col items-center mt-202">
      <text class="text text_2">智游伴</text>
      <text class="mt-10 text text_3">智游伴支持IPv6网络</text>
    </view>
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
  .mt-202 {
    margin-top: 385.5rpx;
  }
  .page {
    padding: 217.56rpx 0 156.49rpx;
    background-color: #ffffff;
    border-left: solid 1.91rpx #d9d9d9;
    border-right: solid 1.91rpx #d9d9d9;
    border-top: solid 1.91rpx #d9d9d9;
    border-bottom: solid 1.91rpx #d9d9d9;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
    height: 100%;
  }
  .image {
    width: 100vw;
    height: 101.7812vw;
  }
  .text {
    font-style: italic;
  }
  .text_2 {
    color: #55b0dd;
    font-size: 61.07rpx;
    font-family: Inter;
    line-height: 57.82rpx;
  }
  .text_3 {
    color: #000000b3;
    font-size: 22.9rpx;
    font-family: Inter;
    line-height: 21.87rpx;
  }
</style>