<template>
  <view class="flex-col justify-start page">
    <view class="flex-col group">
      <view class="flex-col justify-start items-start self-start text-wrapper"><text class="text">黄鹤楼</text></view>
      <view class="mt-98 flex-col self-stretch section">
        <view class="flex-row justify-between items-center group_2">
          <view class="flex-row items-center">
            <image
              class="shrink-0 image_2"
              src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=7e62ed1a05040ac759d4e3474e18acd4.png"
            />
            <text class="ml-4 text_2">Pay</text>
          </view>
          <image
            class="image"
            src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=c6c877105aed2de3b43ad52abf8cb1ef.png"
          />
        </view>
        <view class="mt-24 flex-col justify-start relative group_3">
          <view class="flex-col list">
            <view class="flex-col relative mt-8 list-item section_2" v-for="(item, index) in items" :key="index">
              <view class="flex-row justify-between items-end self-stretch">
                <view class="flex-col items-start">
                  <text class="font">Apple Card</text>
                  <text class="font_2 text_3 mt-9">10880 Malibu Point Malibu Cal...</text>
                </view>
                <image
                  class="image_4"
                  src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=ce07b51a96a7276da4f3b3f0012ab4b8.png"
                />
              </view>
              <text class="self-start font_2 text_4">•••• 1234</text>
              <image
                class="shrink-0 image_3 pos"
                src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=45046557dd3f503aefcc6ead1daf9668.png"
              />
            </view>
          </view>
          <view class="flex-col section_3 pos_4">
            <view class="flex-row justify-between items-center self-stretch group_6">
              <view class="flex-col items-start">
                <text class="font_4">Pay Stark Industries</text>
                <text class="mt-6 text_11">$1.99</text>
              </view>
              <image
                class="image_4"
                src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=0eddbcddf61a4155d59b20e870678307.png"
              />
            </view>
            <image
              class="self-center image_6"
              src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=62b51934464cedc702054dfad1360e8c.png"
            />
            <text class="self-center font_4 text_15">Pay with TouchID</text>
          </view>
        </view>
      </view>
    </view>
  </view>
</template>

<script>
  export default {
    components: {},
    props: {},
    data() {
      return {
        items: [null, null, null, null],
      };
    },

    methods: {},
  };
</script>

<style scoped lang="css">
  .mt-9 {
    margin-top: 17.18rpx;
  }
  .page {
    padding-top: 112.6rpx;
    background-color: #ffffff;
    height: 100%;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
  }
  .group {
    margin-left: 41.98rpx;
    padding-top: 47.71rpx;
    overflow: hidden;
  }
  .text-wrapper {
    margin-left: 19.08rpx;
    padding: 15.27rpx 0 332.06rpx;
    background-image: url('https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=f7150d3bdc2ea43892646ac5b12c6857.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
    width: 629.77rpx;
  }
  .text {
    margin-left: 26.72rpx;
    color: #ffffff;
    font-size: 45.8rpx;
    font-family: STIX Two Text;
    font-weight: 600;
    line-height: 43.32rpx;
  }
  .section {
    padding-top: 30.53rpx;
    backdrop-filter: blur(76.34rpx);
    overflow: hidden;
    background-image: url('https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=06c1fc16db8a6ae7ea6dc630a01cccc0.png');
    background-size: 100% 100%;
  }
  .group_2 {
    padding-left: 30.53rpx;
    padding-right: 22.9rpx;
  }
  .image_2 {
    width: 34.35rpx;
    height: 41.98rpx;
  }
  .text_2 {
    color: #000000;
    font-size: 45.8rpx;
    font-family: SF Pro Display;
    line-height: 40.1rpx;
  }
  .image {
    border-radius: 190.84rpx;
    backdrop-filter: blur(51.87rpx);
    width: 57.25rpx;
    height: 57.25rpx;
  }
  .group_3 {
    height: 754.01rpx;
  }
  .list {
    margin-left: 30.53rpx;
    margin-right: 22.9rpx;
  }
  .list-item {
    padding: 38.17rpx 30.53rpx 38.17rpx 110.69rpx;
    background-color: #ffffff;
    border-radius: 24.81rpx;
    overflow: hidden;
  }
  .list-item:first-child {
    margin-top: 0;
  }
  .section_2 {
    padding: 38.17rpx 30.53rpx 38.17rpx 125.95rpx;
    background-color: #ffffff;
    border-radius: 24.81rpx;
    overflow: hidden;
  }
  .font {
    font-size: 28.63rpx;
    font-family: SF Pro Text;
    line-height: 26.09rpx;
    color: #000000;
  }
  .font_2 {
    font-size: 24.81rpx;
    font-family: SF Pro Text;
    line-height: 18.47rpx;
    color: #3c3c4399;
  }
  .text_3 {
    line-height: 18.89rpx;
  }
  .image_4 {
    width: 15.27rpx;
    height: 26.72rpx;
  }
  .text_4 {
    margin-top: 19.08rpx;
    line-height: 18.19rpx;
  }
  .image_3 {
    border-radius: 1.91rpx;
    width: 76.34rpx;
    height: 47.71rpx;
  }
  .pos {
    position: absolute;
    left: 30.53rpx;
    top: 30.53rpx;
  }
  .font_4 {
    font-size: 24.81rpx;
    font-family: SF Pro Text;
    line-height: 23.07rpx;
    color: #3c3c4399;
  }
  .section_3 {
    background-color: #fafafaed;
    backdrop-filter: blur(76.34rpx);
  }
  .pos_4 {
    position: absolute;
    left: 0;
    right: 0;
    top: 471.37rpx;
  }
  .group_6 {
    padding: 38.17rpx 22.9rpx 38.17rpx 34.35rpx;
    border-top: solid 0.95rpx #3c3c435c;
    border-bottom: solid 0.95rpx #3c3c435c;
  }
  .text_11 {
    color: #000000;
    font-size: 53.44rpx;
    font-family: SF Pro Rounded;
    line-height: 45.97rpx;
  }
  .image_6 {
    margin-top: 30.53rpx;
    opacity: 0.5;
    width: 55.34rpx;
    height: 53.44rpx;
  }
  .text_15 {
    margin-top: 19.08rpx;
    color: #000000;
  }
</style>