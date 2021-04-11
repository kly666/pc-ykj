<template>
  <section class="footer">
    <div class="w footer-content">
      <div>
        <div class="footer-title">
          <img src="~assets/img/logo.png" alt="" />
          <div class="sub-title">
            <h2>异空间APP</h2>
            <p>守护你的秘密</p>
          </div>
        </div>
        <div class="fotter-info">
          <p>Copyright © 2020-2020 异空间, All Rights Reserved.</p>
          <p>
            <a
              href="https://beian.miit.gov.cn/#/Integrated/index"
              style="color: #fff"
              >粤ICP备2020122647号</a
            >
            &nbsp;
            <img src="~assets/img/beian.png" alt="" />
            &nbsp;粤公网安备44070502000517号
          </p>
        </div>
      </div>
      <div>
        <div class="erweima">
          <img src="~assets/img/erweima_gzh.jpg" alt="" />
        </div>
        <p class="gzh">异空间公众号</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="less">
.footer {
  height: 230px;
  background-color: #595959;
}
.footer-content {
  display: flex;
  flex-wrap: nowrap;
  flex-direction: row;
  justify-content: space-between;
  padding-top: 30px;
  .footer-title {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    img {
      width: 82px;
      height: 82px;
    }
    .sub-title {
      padding: 10px;
      padding-left: 15px;
      h2 {
        font-size: 30px;
        color: #fff;
      }
      p {
        opacity: 0.5;
        font-size: 20px;
        color: #fff;
      }
    }
  }
  .fotter-info {
    margin-top: 20px;
    p {
      opacity: 0.5;
      font-size: 16px;
      color: #fff;
      margin-top: 5px;
    }
    img {
      width: 20px;
      height: 20px;
      margin: -2px;
    }
  }
  .erweima {
    margin-right: 10px;

    img {
      width: 120px;
    }
  }
  .gzh {
    margin-right: 10px;
    text-align: center;
    font-size: 16px;
    color: #fff;
    margin-top: 5px;
  }
}
</style>