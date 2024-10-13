<template>
  <view class="flex-col page">
    <view class="flex-col self-stretch">
      <view class="flex-row items-center self-center section">
        <image
          class="shrink-0 image"
          src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=e4858066474f1e65880788aa7bfda436.png"
        />
        <view class="ml-4 group">
          <text class="font text">
            黄鹤楼
            <br />
          </text>
          <text class="font text_2">湖北武汉武昌区</text>
        </view>
      </view>
      <view class="flex-col justify-start items-center self-stretch text-wrapper">
        <text class="text_3">主楼</text>
      </view>
      <text class="self-center text_4">AR旅行</text>
    </view>
    <view class="mt-18 flex-row justify-center items-center self-center section_2">
      <image
        class="image_2"
        src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=01f3b83fa3ae6db12448b8ce55104d03.png"
      />
      <text class="ml-4 text_5">查看地点详情</text>
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
  .page {
    padding: 112.6rpx 0 51.53rpx;
    background-color: #231016;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
    height: 100%;
  }
  .section {
    padding: 0 19.08rpx;
    background-color: #00000066;
    border-radius: 38.17rpx;
  }
  .image {
    width: 38.17rpx;
    height: 38.17rpx;
  }
  .group {
    margin-right: 19.08rpx;
    height: 80.32rpx;
  }
  .font {
    font-size: 24.81rpx;
    font-family: STIX Two Text;
    line-height: 40.08rpx;
  }
  .text {
    color: #ffffff;
  }
  .text_2 {
    color: #c4c4c4;
  }
  .text-wrapper {
    margin-right: 9.54rpx;
    margin-top: 11.45rpx;
    padding: 49.62rpx 0 1083.97rpx;
    filter: drop-shadow(0rpx 7.63rpx 3.82rpx #00000040);
    background-image: url('https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=86b1a4f1ed5ba6efeb9452db3eaae0f1.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .text_3 {
    color: #ffffff;
    font-size: 30.53rpx;
    font-family: Poppins;
    font-weight: 600;
    line-height: 28.82rpx;
  }
  .text_4 {
    margin-top: 24.81rpx;
    color: #ffffff;
    font-size: 76.34rpx;
    font-family: STIX Two Text;
    font-weight: 600;
    line-height: 71.98rpx;
  }
  .section_2 {
    padding: 15.27rpx 0;
    background-color: #00000066;
    border-radius: 38.17rpx;
    width: 616.41rpx;
  }
  .image_2 {
    margin-left: 185.11rpx;
    width: 45.8rpx;
    height: 45.8rpx;
  }
  .text_5 {
    margin-right: 194.66rpx;
    color: #ffffff;
    font-size: 30.53rpx;
    font-family: STIX Two Text;
    line-height: 28.24rpx;
  }
</style>