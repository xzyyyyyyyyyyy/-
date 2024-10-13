<template>
  <view class="flex-col page">
    <view class="flex-col self-stretch group">
      <view class="flex-col justify-start items-start text-wrapper"><text class="font text">黄鹤楼</text></view>
      <view class="flex-col justify-start items-start relative text-wrapper_2">
        <text class="font text_2">汉口里</text>
      </view>
      <view class="flex-col justify-start items-start relative text-wrapper_3">
        <text class="font text_3">步行街</text>
      </view>
    </view>
    <image
      class="self-center image mt-85"
      src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=4ea553d2fd82a573a8f75a9ffc074a1c.png"
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
  .mt-85 {
    margin-top: 162.21rpx;
  }
  .page {
    padding: 160.31rpx 28.63rpx 320.61rpx;
    background-color: #f2f2f7;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
    height: 100%;
  }
  .group {
    height: 719.47rpx;
  }
  .text-wrapper {
    margin: 0 30.53rpx;
    padding: 15.27rpx 0 332.06rpx;
    background-image: url('https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=f7150d3bdc2ea43892646ac5b12c6857.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .font {
    font-size: 45.8rpx;
    font-family: STIX Two Text;
    line-height: 43.05rpx;
    font-weight: 600;
    color: #ffffff;
  }
  .text {
    margin-left: 26.72rpx;
    line-height: 43.32rpx;
  }
  .text-wrapper_2 {
    margin: -263.36rpx 11.45rpx 0;
    padding: 15.27rpx 0 370.23rpx;
    background-image: url('https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=f6faced4d8e48f6c7b2daaaab899a576.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .text_2 {
    margin-left: 34.35rpx;
    line-height: 42.1rpx;
  }
  .text-wrapper_3 {
    margin-top: -269.08rpx;
    padding: 19.08rpx 0 370.23rpx;
    background-image: url('https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=c1b5bd360aa1593ee2088b66211440d0.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .text_3 {
    margin-left: 22.9rpx;
  }
  .image {
    width: 286.26rpx;
    height: 263.36rpx;
  }
</style>