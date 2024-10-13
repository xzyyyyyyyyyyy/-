<template>
  <view class="flex-col page">
    <view class="flex-col section">
      <view class="flex-row justify-center items-center relative group">
        <text class="text text_2">计划</text>
        <image
          class="image pos"
          src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=c54c8dbdd824af3d49269a7362f95d15.png"
        />
      </view>
      <view class="flex-col section_2">
        <view class="flex-row justify-between items-center group_2">
          <text class="font text text_3">10月11日</text>
          <view class="flex-row items-center">
            <image
              class="image_3"
              src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=36e140f365ba17e2bcee38ba973d6236.png"
            />
            <image
              class="image_2 ml-17"
              src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=ca65cd6829a421d500ab9036f9336bbc.png"
            />
          </view>
        </view>
        <view class="flex-row justify-between items-center mt-15">
          <view class="flex-col">
            <view class="flex-row group_3">
              <text class="font_2 text_4">S</text>
              <text class="ml-32 font_2 text_5">M</text>
              <text class="ml-32 font_2 text_6">T</text>
              <text class="ml-32 font_2 text_7">W</text>
            </view>
            <view class="flex-row mt-23">
              <text class="font_3">18</text>
              <text class="font_3 ml-25">19</text>
              <text class="font_3 ml-25">20</text>
              <text class="font_4 text_11 ml-25">21</text>
            </view>
          </view>
          <view class="flex-col items-center section_3">
            <text class="font_2 text_8">T</text>
            <text class="font_4 text_12 mt-23">22</text>
          </view>
          <view class="flex-col">
            <view class="flex-row group_4">
              <text class="font_2 text_9">F</text>
              <text class="ml-36 font_2 text_10">S</text>
            </view>
            <view class="flex-row mt-23">
              <text class="font_3">23</text>
              <text class="font_4 text_13 ml-25">24</text>
            </view>
          </view>
        </view>
      </view>
      <view class="flex-col group_5">
        <view class="flex-row justify-between items-baseline">
          <text class="font text text_14">我的计划</text>
          <text class="text_15">全部</text>
        </view>
        <view class="flex-col group_4 mt-17">
          <view class="flex-row relative list-item section_4 mt-17" v-for="(item, index) in items" :key="index">
            <image
              class="shrink-0 self-center image_4"
              src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=492e5ae71c48d1ae8c16801fb09c2137.png"
            />
            <view class="flex-col flex-1 self-center group_6">
              <view class="flex-row items-center self-stretch group_7">
                <image
                  class="shrink-0 image_5"
                  src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=57dd2f56126c8f5356ab3a6c208d5e03.png"
                />
                <text class="font_5 ml-7">26 January 2022</text>
              </view>
              <text class="self-start font_6 text_16">江汉路步行街</text>
              <view class="flex-row items-center self-stretch group_8">
                <image
                  class="image_7"
                  src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=85f55931b1a71ec39583b56676f4ef77.png"
                />
                <text class="ml-4 font_6">湖北，武汉</text>
              </view>
            </view>
            <image
              class="shrink-0 self-start image_2 image_6"
              src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=4539695000877b063ce83abe0c9b2bba.png"
            />
          </view>
        </view>
      </view>
    </view>
    <view class="flex-row justify-between items-end relative group_11">
      <view class="flex-col items-center group_12">
        <image
          class="image_13"
          src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=2546da2555b91c5f4e17cc1474c2d62d.png"
        />
        <text class="mt-6 font_8 text_19">主页</text>
      </view>
      <image
        class="image_12"
        src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=07374155480180d798735b1a8f689d98.png"
      />
      <view class="flex-col items-center group_13">
        <image
          class="image_13"
          src="https://ide.code.fun/api/image?token=670b89f570ac1f0012ce8ccd&name=17ba6fbb3a7db523240a8ad4c049a400.png"
        />
        <text class="mt-6 font_8 text_20">我的</text>
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
        items: [null, null, null],
      };
    },

    methods: {},
  };
</script>

<style scoped lang="css">
  .ml-17 {
    margin-left: 32.44rpx;
  }
  .mt-15 {
    margin-top: 28.63rpx;
  }
  .ml-25 {
    margin-left: 47.71rpx;
  }
  .ml-7 {
    margin-left: 13.36rpx;
  }
  .mt-23 {
    margin-top: 43.89rpx;
  }
  .mt-17 {
    margin-top: 32.44rpx;
  }
  .page {
    padding-bottom: 24.81rpx;
    background-color: #f2f2f7;
    border-radius: 57.25rpx;
    height: 100%;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
  }
  .section {
    padding: 114.5rpx 30.53rpx 133.59rpx;
    background-color: #ffffff;
    border-radius: 57.25rpx 57.25rpx 0rpx 0rpx;
  }
  .group {
    padding: 19.08rpx 15.27rpx 26.72rpx;
  }
  .image {
    border-radius: 50%;
    width: 85.02rpx;
    height: 88.11rpx;
  }
  .pos {
    position: absolute;
    right: 15.61rpx;
    top: 50%;
    transform: translateY(-50%);
  }
  .section_2 {
    margin: 57.25rpx 15.27rpx 0 26.72rpx;
    padding: 34.35rpx 30.53rpx 30.53rpx;
    background-color: #ffffff;
    border-radius: 45.8rpx;
    box-shadow: 0rpx 11.45rpx 38.17rpx #b3bcc829;
  }
  .group_2 {
    padding-left: 38.17rpx;
  }
  .font {
    font-size: 38.17rpx;
    font-family: Inter;
    color: #000000;
  }
  .text {
    font-style: italic;
  }
  .text_2 {
    color: #000000;
    font-size: 45.8rpx;
    font-family: Inter;
    line-height: 42.96rpx;
  }
  .text_3 {
    line-height: 34.05rpx;
  }
  .image_3 {
    width: 11.45rpx;
    height: 22.9rpx;
  }
  .image_2 {
    width: 45.8rpx;
    height: 47.71rpx;
  }
  .group_3 {
    padding-left: 7.63rpx;
  }
  .font_2 {
    font-size: 30.53rpx;
    font-family: SF UI Display;
    line-height: 20.17rpx;
    color: #7c838d;
  }
  .text_4 {
    font-size: 28.63rpx;
    line-height: 20.84rpx;
  }
  .text_5 {
    font-size: 28.63rpx;
  }
  .text_6 {
    font-size: 28.63rpx;
  }
  .text_7 {
    font-size: 28.63rpx;
  }
  .font_3 {
    font-size: 30.53rpx;
    font-family: SF UI Display;
    line-height: 22.39rpx;
    font-weight: 600;
    color: #1b1e28;
  }
  .font_4 {
    font-size: 30.53rpx;
    font-family: SF UI Display;
    line-height: 20.17rpx;
    font-weight: 600;
    color: #1b1e28;
  }
  .text_11 {
    line-height: 21.95rpx;
  }
  .section_3 {
    padding: 34.35rpx 0;
    background-color: #ff7029;
    border-radius: 22.9rpx;
    width: 85.02rpx;
    height: 152.18rpx;
  }
  .text_8 {
    color: #d0d9e6;
    font-size: 28.63rpx;
  }
  .text_12 {
    color: #ffffff;
    line-height: 21.95rpx;
  }
  .group_4 {
    padding: 0 11.45rpx;
  }
  .text_9 {
    font-size: 28.63rpx;
  }
  .text_10 {
    font-size: 28.63rpx;
    line-height: 20.84rpx;
  }
  .text_13 {
    line-height: 21.95rpx;
  }
  .group_5 {
    margin-top: 64.89rpx;
  }
  .text_14 {
    line-height: 36.03rpx;
  }
  .text_15 {
    margin-right: 41.98rpx;
    color: #24baec;
    font-size: 26.72rpx;
    font-family: Microsoft YaHei;
    line-height: 25.84rpx;
  }
  .list-item {
    margin-right: 22.9rpx;
  }
  .list-item:first-child {
    margin-top: 0;
  }
  .section_4 {
    padding: 30.53rpx 15.27rpx 7.63rpx;
    background-color: #ffffff;
    border-radius: 30.53rpx;
    box-shadow: 0rpx 11.45rpx 30.53rpx #b3bcc81f;
  }
  .image_4 {
    border-radius: 43.89rpx;
    width: 160.31rpx;
    height: 158.4rpx;
  }
  .group_6 {
    margin-left: 30.53rpx;
  }
  .group_7 {
    padding-left: 3.82rpx;
  }
  .image_5 {
    width: 30.53rpx;
    height: 32.44rpx;
  }
  .font_5 {
    font-size: 24.81rpx;
    font-family: SF UI Display;
    line-height: 22.52rpx;
    color: #7c838d;
  }
  .font_6 {
    font-size: 24.81rpx;
    font-family: Microsoft YaHei UI;
    line-height: 24.01rpx;
    color: #7d848d;
  }
  .text_16 {
    margin-left: 3.82rpx;
    margin-top: 26.72rpx;
    color: #000000;
    line-height: 24.24rpx;
  }
  .group_8 {
    margin-top: 41.98rpx;
  }
  .image_7 {
    width: 32.44rpx;
    height: 34.35rpx;
  }
  .image_6 {
    margin: 45.8rpx 3.82rpx 0 38.17rpx;
  }
  .group_11 {
    margin-top: -87.79rpx;
    padding: 0 87.79rpx;
  }
  .group_12 {
    margin-bottom: 7.63rpx;
  }
  .image_13 {
    width: 45.8rpx;
    height: 45.8rpx;
  }
  .font_8 {
    font-size: 24.81rpx;
    font-family: Poppins;
    line-height: 20.17rpx;
    font-weight: 600;
    color: #000000;
  }
  .text_19 {
    font-size: 22.9rpx;
    line-height: 21.6rpx;
  }
  .image_12 {
    width: 364.5rpx;
    height: 198.47rpx;
  }
  .group_13 {
    margin-bottom: 7.63rpx;
  }
  .text_20 {
    font-size: 22.9rpx;
    line-height: 21.62rpx;
  }
</style>