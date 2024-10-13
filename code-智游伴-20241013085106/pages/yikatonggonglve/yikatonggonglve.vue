<template>
  <view class="flex-col page">
    <view class="flex-col">
      <text class="self-stretch font text">
        《App 一卡通 NFC 功能绑定指南》  一、准备工作 1. 确保你的手机支持 NFC
        功能。可以在手机设置中查找“连接与共享”等选项，确认是否有 NFC 开关。
        <br />
      </text>
      <text class="self-start font">
        2. 下载并安装我们的 智游伴。
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
          
      </text>
    </view>
    <view class="flex-col group">
      <view class="flex-col justify-start items-start relative">
        <image
          class="image"
          src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=731ea44cf3e30b33fd82a3269a293e54.png"
        />
        <view class="section pos"></view>
      </view>
      <text class="mt-20 font">
        二、绑定步骤 1. 打开 App，在快捷操作中找到“”NFC板块，点击进入。 2. 在一卡通页面中，寻找“绑定一卡通” 3.
        此时，系统可能会要求你创建虚拟卡，并将实体卡写入 4. 提交信息后，App
        会进行验证。验证成功后，你的一卡通就成功绑定到 App 上了。  
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
      </text>
    </view>
    <view class="flex-row justify-between group_2">
      <image
        class="image_2"
        src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=c1501d8233f733204ef3a1372a836f4f.png"
      />
      <view class="flex-col items-start self-start group_3">
        <text class="text_2">智游伴一卡通</text>
        <text class="mt-32 text_3">请把卡片紧贴在手机背面</text>
      </view>
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
    padding: 236.64rpx 38.17rpx 0 41.98rpx;
    background-color: #e9e8e8;
    height: 100%;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
  }
  .font {
    font-size: 28.63rpx;
    font-family: Inter;
    line-height: 41.98rpx;
    color: #000000;
  }
  .text {
    text-indent: 111.03rpx;
  }
  .group {
    margin-right: 15.27rpx;
    margin-top: 19.08rpx;
  }
  .image {
    margin-left: 41.98rpx;
    width: 204.2rpx;
    height: 446.56rpx;
  }
  .section {
    border-radius: 190.84rpx;
    background-color: #00000000;
    width: 255.73rpx;
    height: 9.54rpx;
  }
  .pos {
    position: absolute;
    left: 50%;
    top: 187.02rpx;
    transform: translateX(-50%);
  }
  .group_2 {
    margin: 38.17rpx 0 -229.01rpx;
    padding: 0 41.98rpx;
  }
  .image_2 {
    width: 200.38rpx;
    height: 446.56rpx;
  }
  .group_3 {
    margin-top: 30.53rpx;
    width: 254.39rpx;
  }
  .text_2 {
    margin-left: 15.27rpx;
    color: #000000;
    font-size: 11.45rpx;
    font-family: Microsoft YaHei;
    line-height: 11.11rpx;
  }
  .text_3 {
    color: #000000;
    font-size: 15.27rpx;
    font-family: Inter;
    line-height: 14.08rpx;
  }
</style>