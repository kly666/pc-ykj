<template>
  <div class="main">
    <div class="w main-content">
      <div class="text-group">
        <h1>异空间</h1>
        <h2>隐藏各种格式文件数据</h2>
        <h2>守护你的手机秘密</h2>
        <h2>让隐私数据更安全</h2>
        <div class="download">
          <a
            href="http://oss.tuzidewang.xyz//apks/154544c9a29e4f7f81bfa5f999ee6690.apk"
          >
            <img src="~assets/img/android.png" alt="" />
          </a>
        </div>
      </div>
      <div class="image-group">
        <div class="first-index">
          <img src="~assets/img/images/main_img1.png" alt="" />
        </div>
        <div class="second-index">
          <img src="~assets/img/images/main_img2.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style lang="less">
.main {
  height: 550px;
  padding-top: 50px;
  // background-color: #00a667;
  background-image: linear-gradient(to right, #8a6441, #c2bb9b, #b29f94);
}
.main-content {
  display: flex;
  justify-content: space-between;
}
.text-group {
  margin-top: 50px;
  width: 500px;
}
.text-group h1 {
  font-size: 56px;
  color: #fff;
  font-weight: 400;
  margin-top: 10px;
}
.text-group h2 {
  opacity: 0.95;
  font-size: 30px;
  color: #fff;
  font-weight: 400;
  margin-top: 20px;
}
.download {
  margin-top: 50px;
  img {
    width: 50%;
  }
}

.image-group {
  position: relative;
  width: 500px;
  .first-index {
    position: absolute;
    top: -20px;
    left: 0;
    width: 75%;
    // border: 1px solid red;
    border-radius: 20px;
    // box-shadow: 5px 0 2px rgba(104, 101, 101, 0.5);
    overflow: hidden;
    z-index: 1;
  }
  .second-index {
    position: absolute;
    top: -40px;
    right: -95px;
    width: 75%;
    // border: 1px solid red;
    // box-shadow: 5px 0 2px rgba(119, 115, 115, 0.5);
    border-radius: 20px;
    overflow: hidden;
  }
  img {
    width: 100%;
  }
}
</style>