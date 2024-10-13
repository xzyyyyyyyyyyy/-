<template>
  <view class="flex-col page">
    <view class="flex-row items-center group">
      <view class="flex-col justify-start items-center text-wrapper"><text class="text">9:41</text></view>
      <view class="flex-col justify-start items-end section"><view class="section_2"></view></view>
      <view class="flex-row group_2">
        <image
          class="image"
          src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=ce1366be794f29c326a89e460008d665.png"
        />
        <image
          class="ml-8 image_2"
          src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=8721bccf47d27254ea4a80b57560355f.png"
        />
        <image
          class="ml-8 image_3"
          src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=62c93dc9073979a57d81531219853a37.png"
        />
      </view>
    </view>
    <image
      class="image_4"
      src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=3fd7d085c3cd923c813d4bb5f05d130c.png"
    />
    <view class="flex-col items-center group_3">
      <text class="text_2 text_3">智游伴</text>
      <text class="mt-10 text_2 text_4">智游伴支持IPv6网络</text>
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
    padding: 22.9rpx 0 156.49rpx;
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
  .group {
    padding-left: 87.79rpx;
    padding-right: 61.07rpx;
  }
  .text-wrapper {
    padding: 11.45rpx 0;
    border-radius: 45.8rpx;
    width: 103.05rpx;
    height: 40.08rpx;
  }
  .text {
    color: #000000;
    font-size: 30.53rpx;
    font-family: STIX Two Text;
    font-weight: 600;
    line-height: 20.11rpx;
  }
  .section {
    margin-left: 66.79rpx;
    background-color: #000000;
    border-radius: 190.84rpx;
    width: 238.55rpx;
    height: 70.61rpx;
  }
  .section_2 {
    background-color: #000000;
    border-radius: 190.84rpx;
    overflow: hidden;
    width: 70.61rpx;
    height: 70.61rpx;
  }
  .group_2 {
    margin-left: 41.98rpx;
  }
  .image {
    width: 34.35rpx;
    height: 22.9rpx;
  }
  .image_2 {
    width: 32.44rpx;
    height: 22.9rpx;
  }
  .image_3 {
    width: 51.53rpx;
    height: 24.81rpx;
  }
  .image_4 {
    margin-top: 122.14rpx;
    width: 100vw;
    height: 101.7812vw;
  }
  .group_3 {
    margin-top: 385.5rpx;
  }
  .text_2 {
    font-style: italic;
  }
  .text_3 {
    color: #55b0dd;
    font-size: 61.07rpx;
    font-family: Inter;
    line-height: 57.82rpx;
  }
  .text_4 {
    color: #000000b3;
    font-size: 22.9rpx;
    font-family: Inter;
    line-height: 21.87rpx;
  }
</style>