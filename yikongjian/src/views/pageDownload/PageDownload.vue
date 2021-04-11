<template>
  <div class="page-download">
    <div class="w page-download-content">
      <div class="title">
        <h1>打开异空间，守护私密数据文件</h1>
        <h2>放心存，无泄漏</h2>
      </div>
      <div class="erweima">
        <img src="~assets/img/erweima.png" alt="" />
        <p>扫码下载APP</p>
      </div>
      <div class="download">
        <a
          href="http://oss.tuzidewang.xyz//apks/154544c9a29e4f7f81bfa5f999ee6690.apk"
        >
          <img src="~assets/img/android.png" alt="" />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PageDownload",
};
</script>

<style lang="less">
.page-download {
  height: 600px;
  // background: url(~assets/img/backgroud.jpg);
  background-image: linear-gradient(to right, #f0e8ee, #dddcd7, #d7dadf);
  .page-download-content {
    padding-top: 100px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-content: center;
    .title {
      text-align: center;
      h1 {
        color: #333;
        font-size: 56px;
      }
      h2 {
        margin-top: 20px;
        color: #666;
        font-size: 27px;
      }
    }
    .erweima {
      width: 100%;
      margin-top: 20px;
      text-align: center;
      img {
        width: 130px;
      }
      p {
        margin-top: 5px;
      }
    }
    .download {
      text-align: center;
      margin-top: 20px;
      img {
        width: 38%;
      }
    }
  }
}
</style>