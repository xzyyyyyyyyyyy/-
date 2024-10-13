<template>
  <view class="flex-col page">
    <text class="self-center text text_2">现在登录</text>
    <text class="self-center text text_3">请登录以使用我们的软件</text>
    <view class="flex-col self-stretch group">
      <view class="flex-col self-stretch group_2">
        <text class="self-start font text_4">账号</text>
        <view class="mt-4 flex-col justify-start items-center self-stretch text-wrapper">
          <text class="font_2 text_5">输入账号</text>
        </view>
        <text class="mt-4 self-start font text_6">密码</text>
      </view>
      <view class="flex-row justify-center items-center self-stretch relative section">
        <image
          class="image_2 pos_2"
          src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=ddbd48b587be686b7088f268808021eb.png"
        />
        <text class="font_2 text_7">输入密码</text>
        <image
          class="image pos"
          src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=853d02ea4ee34a45ae189f1bff5ee0a8.png"
        />
      </view>
      <text class="self-end font_3 text text_8">忘记密码？</text>
    </view>
    <view class="flex-col justify-start items-center self-stretch text-wrapper_2">
      <text class="text text_9">登录</text>
    </view>
    <view class="flex-col self-stretch group_3">
      <text class="self-center font_3 text text_10">没有账号?</text>
      <text class="self-center font_3 text text_11">注册账号</text>
      <view class="flex-col items-center self-stretch group_4">
        <text class="text text_12">或者用第三方登录</text>
        <image
          class="mt-24 image_3"
          src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=c87e314ddf7d21890f4224c225652207.png"
        />
      </view>
    </view>
    <view class="flex-row justify-center items-center self-stretch group_5">
      <view class="section_2"></view>
      <text class="ml-6 font_3 text text_13">已阅读并同意服务协议和隐私保护指引</text>
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
    padding: 198.47rpx 19.08rpx 68.7rpx;
    background-color: #ffffff;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
    height: 100%;
  }
  .group {
    margin-top: 49.62rpx;
  }
  .group_2 {
    padding-bottom: 15.27rpx;
  }
  .font {
    font-size: 30.53rpx;
    font-family: Poppins;
    line-height: 28.95rpx;
    font-weight: 900;
    color: #000000;
  }
  .text_4 {
    margin-left: 15.27rpx;
    line-height: 28.19rpx;
  }
  .text-wrapper {
    padding: 41.98rpx 0;
    background-color: #f6f6f8;
    border-radius: 26.72rpx;
  }
  .font_2 {
    font-size: 30.53rpx;
    font-family: Microsoft YaHei;
    line-height: 28.95rpx;
    color: #00000033;
  }
  .text_5 {
    line-height: 29.48rpx;
  }
  .text_6 {
    margin-left: 15.27rpx;
    line-height: 28.65rpx;
  }
  .section {
    padding: 41.98rpx 22.9rpx 41.98rpx 34.35rpx;
    background-color: #f6f6f8;
    border-radius: 26.72rpx;
  }
  .image_2 {
    width: 206.11rpx;
    height: 17.18rpx;
  }
  .pos_2 {
    position: absolute;
    left: 34.06rpx;
    top: 50%;
    transform: translateY(-50%);
  }
  .text_7 {
    line-height: 29.69rpx;
  }
  .image {
    width: 53.44rpx;
    height: 51.53rpx;
  }
  .pos {
    position: absolute;
    right: 22.25rpx;
    top: 50%;
    transform: translateY(-50%);
  }
  .font_3 {
    font-size: 26.72rpx;
    font-family: Inter;
    line-height: 25.38rpx;
  }
  .text {
    font-style: italic;
  }
  .text_3 {
    margin-top: 83.97rpx;
    color: #000000;
    font-size: 30.53rpx;
    font-family: Inter;
    line-height: 28.95rpx;
  }
  .text_2 {
    color: #000000;
    font-size: 68.7rpx;
    font-family: Inter;
    line-height: 64.85rpx;
  }
  .text_8 {
    margin-top: 53.44rpx;
    color: #670000;
    line-height: 25.1rpx;
  }
  .text-wrapper_2 {
    margin-top: 72.52rpx;
    padding: 38.17rpx 0 34.35rpx;
    background-color: #eed600;
    border-radius: 30.53rpx;
  }
  .text_9 {
    color: #000000;
    font-size: 45.8rpx;
    font-family: Inter;
    line-height: 43.05rpx;
  }
  .group_3 {
    margin-top: 72.52rpx;
    padding: 0 167.94rpx;
  }
  .text_10 {
    color: #000000;
    line-height: 25.19rpx;
  }
  .text_11 {
    margin-top: 34.35rpx;
    color: #670101;
  }
  .group_4 {
    margin-top: 45.8rpx;
  }
  .text_12 {
    color: #000000;
    font-size: 20.99rpx;
    font-family: Inter;
    line-height: 20.06rpx;
  }
  .image_3 {
    width: 377.86rpx;
    height: 135.5rpx;
  }
  .group_5 {
    margin-top: 110.69rpx;
  }
  .section_2 {
    background-color: #d9d9d9;
    border-radius: 50%;
    width: 28.63rpx;
    height: 28.63rpx;
  }
  .text_13 {
    color: #000000b3;
    line-height: 25.57rpx;
  }
</style>