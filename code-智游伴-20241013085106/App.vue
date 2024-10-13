<script>
  export default {
    onLaunch: function () {
      console.log('App Launch');
    },
    onShow: function () {
      console.log('App Show');
    },
    onHide: function () {
      console.log('App Hide');
    },
  };
</script>

<style>
    /************************************************************
  ** 请将全局样式拷贝到项目的全局 CSS 文件或者当前页面的顶部 **
  ** 否则页面将无法正常显示                                  **
  ************************************************************/

  html {
    font-size: 16px;
  }

  body {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell', 'Fira Sans',
      'Droid Sans', 'Helvetica Neue', 'Microsoft Yahei', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  view,
  image,
  text {
    box-sizing: border-box;
    flex-shrink: 0;
  }

  #app {
    width: 100vw;
    height: 100vh;
  }

  .flex-row {
    display: flex;
    flex-direction: row;
  }

  .flex-col {
    display: flex;
    flex-direction: column;
  }

  .justify-start {
    justify-content: flex-start;
  }

  .justify-end {
    justify-content: flex-end;
  }

  .justify-center {
    justify-content: center;
  }

  .justify-between {
    justify-content: space-between;
  }

  .justify-around {
    justify-content: space-around;
  }

  .justify-evenly {
    justify-content: space-evenly;
  }

  .items-start {
    align-items: flex-start;
  }

  .items-end {
    align-items: flex-end;
  }

  .items-center {
    align-items: center;
  }

  .items-baseline {
    align-items: baseline;
  }

  .items-stretch {
    align-items: stretch;
  }

  .self-start {
    align-self: flex-start;
  }

  .self-end {
    align-self: flex-end;
  }

  .self-center {
    align-self: center;
  }

  .self-baseline {
    align-self: baseline;
  }

  .self-stretch {
    align-self: stretch;
  }

  .flex-1 {
    flex: 1 1 0%;
  }

  .flex-auto {
    flex: 1 1 auto;
  }

  .grow {
    flex-grow: 1;
  }

  .grow-0 {
    flex-grow: 0;
  }

  .shrink {
    flex-shrink: 1;
  }

  .shrink-0 {
    flex-shrink: 0;
  }

  .relative {
    position: relative;
  }

  .ml-2 {
    margin-left: 3.82rpx;
  }

  .mt-2 {
    margin-top: 3.82rpx;
  }

  .ml-4 {
    margin-left: 7.63rpx;
  }

  .mt-4 {
    margin-top: 7.63rpx;
  }

  .ml-6 {
    margin-left: 11.45rpx;
  }

  .mt-6 {
    margin-top: 11.45rpx;
  }

  .ml-8 {
    margin-left: 15.27rpx;
  }

  .mt-8 {
    margin-top: 15.27rpx;
  }

  .ml-10 {
    margin-left: 19.08rpx;
  }

  .mt-10 {
    margin-top: 19.08rpx;
  }

  .ml-12 {
    margin-left: 22.9rpx;
  }

  .mt-12 {
    margin-top: 22.9rpx;
  }

  .ml-14 {
    margin-left: 26.72rpx;
  }

  .mt-14 {
    margin-top: 26.72rpx;
  }

  .ml-16 {
    margin-left: 30.53rpx;
  }

  .mt-16 {
    margin-top: 30.53rpx;
  }

  .ml-18 {
    margin-left: 34.35rpx;
  }

  .mt-18 {
    margin-top: 34.35rpx;
  }

  .ml-20 {
    margin-left: 38.17rpx;
  }

  .mt-20 {
    margin-top: 38.17rpx;
  }

  .ml-22 {
    margin-left: 41.98rpx;
  }

  .mt-22 {
    margin-top: 41.98rpx;
  }

  .ml-24 {
    margin-left: 45.8rpx;
  }

  .mt-24 {
    margin-top: 45.8rpx;
  }

  .ml-26 {
    margin-left: 49.62rpx;
  }

  .mt-26 {
    margin-top: 49.62rpx;
  }

  .ml-28 {
    margin-left: 53.44rpx;
  }

  .mt-28 {
    margin-top: 53.44rpx;
  }

  .ml-30 {
    margin-left: 57.25rpx;
  }

  .mt-30 {
    margin-top: 57.25rpx;
  }

  .ml-32 {
    margin-left: 61.07rpx;
  }

  .mt-32 {
    margin-top: 61.07rpx;
  }

  .ml-34 {
    margin-left: 64.89rpx;
  }

  .mt-34 {
    margin-top: 64.89rpx;
  }

  .ml-36 {
    margin-left: 68.7rpx;
  }

  .mt-36 {
    margin-top: 68.7rpx;
  }

  .ml-38 {
    margin-left: 72.52rpx;
  }

  .mt-38 {
    margin-top: 72.52rpx;
  }

  .ml-40 {
    margin-left: 76.34rpx;
  }

  .mt-40 {
    margin-top: 76.34rpx;
  }

  .ml-42 {
    margin-left: 80.15rpx;
  }

  .mt-42 {
    margin-top: 80.15rpx;
  }

  .ml-44 {
    margin-left: 83.97rpx;
  }

  .mt-44 {
    margin-top: 83.97rpx;
  }

  .ml-46 {
    margin-left: 87.79rpx;
  }

  .mt-46 {
    margin-top: 87.79rpx;
  }

  .ml-48 {
    margin-left: 91.6rpx;
  }

  .mt-48 {
    margin-top: 91.6rpx;
  }

  .ml-50 {
    margin-left: 95.42rpx;
  }

  .mt-50 {
    margin-top: 95.42rpx;
  }

  .ml-52 {
    margin-left: 99.24rpx;
  }

  .mt-52 {
    margin-top: 99.24rpx;
  }

  .ml-54 {
    margin-left: 103.05rpx;
  }

  .mt-54 {
    margin-top: 103.05rpx;
  }

  .ml-56 {
    margin-left: 106.87rpx;
  }

  .mt-56 {
    margin-top: 106.87rpx;
  }

  .ml-58 {
    margin-left: 110.69rpx;
  }

  .mt-58 {
    margin-top: 110.69rpx;
  }

  .ml-60 {
    margin-left: 114.5rpx;
  }

  .mt-60 {
    margin-top: 114.5rpx;
  }

  .ml-62 {
    margin-left: 118.32rpx;
  }

  .mt-62 {
    margin-top: 118.32rpx;
  }

  .ml-64 {
    margin-left: 122.14rpx;
  }

  .mt-64 {
    margin-top: 122.14rpx;
  }

  .ml-66 {
    margin-left: 125.95rpx;
  }

  .mt-66 {
    margin-top: 125.95rpx;
  }

  .ml-68 {
    margin-left: 129.77rpx;
  }

  .mt-68 {
    margin-top: 129.77rpx;
  }

  .ml-70 {
    margin-left: 133.59rpx;
  }

  .mt-70 {
    margin-top: 133.59rpx;
  }

  .ml-72 {
    margin-left: 137.4rpx;
  }

  .mt-72 {
    margin-top: 137.4rpx;
  }

  .ml-74 {
    margin-left: 141.22rpx;
  }

  .mt-74 {
    margin-top: 141.22rpx;
  }

  .ml-76 {
    margin-left: 145.04rpx;
  }

  .mt-76 {
    margin-top: 145.04rpx;
  }

  .ml-78 {
    margin-left: 148.85rpx;
  }

  .mt-78 {
    margin-top: 148.85rpx;
  }

  .ml-80 {
    margin-left: 152.67rpx;
  }

  .mt-80 {
    margin-top: 152.67rpx;
  }

  .ml-82 {
    margin-left: 156.49rpx;
  }

  .mt-82 {
    margin-top: 156.49rpx;
  }

  .ml-84 {
    margin-left: 160.31rpx;
  }

  .mt-84 {
    margin-top: 160.31rpx;
  }

  .ml-86 {
    margin-left: 164.12rpx;
  }

  .mt-86 {
    margin-top: 164.12rpx;
  }

  .ml-88 {
    margin-left: 167.94rpx;
  }

  .mt-88 {
    margin-top: 167.94rpx;
  }

  .ml-90 {
    margin-left: 171.76rpx;
  }

  .mt-90 {
    margin-top: 171.76rpx;
  }

  .ml-92 {
    margin-left: 175.57rpx;
  }

  .mt-92 {
    margin-top: 175.57rpx;
  }

  .ml-94 {
    margin-left: 179.39rpx;
  }

  .mt-94 {
    margin-top: 179.39rpx;
  }

  .ml-96 {
    margin-left: 183.21rpx;
  }

  .mt-96 {
    margin-top: 183.21rpx;
  }

  .ml-98 {
    margin-left: 187.02rpx;
  }

  .mt-98 {
    margin-top: 187.02rpx;
  }

  .ml-100 {
    margin-left: 190.84rpx;
  }

  .mt-100 {
    margin-top: 190.84rpx;
  }
</style>