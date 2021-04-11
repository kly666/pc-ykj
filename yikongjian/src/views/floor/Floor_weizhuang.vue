<template>
  <div class="Floor_weizhuang">
    <div class="w weizhuang">
      <div class="top_room">
        <div class="weizhuang_icon">
          <img src="~assets/img/icon/weizhuang_icon.svg" alt="" />
        </div>
        <h1>应用伪装</h1>
        <h2>将你的秘密隐藏在精致的计算器/指南针/日历里</h2>
      </div>
      <div class="bottom_room">
        <img
          src="~assets/img/images/weizhuang_rili.png"
          alt=""
          class="first_img"
        />
        <img
          src="~assets/img/images/weizhuang_zhinanzhen.png"
          alt=""
          class="other_img"
        />
        <img
          src="~assets/img/images/weizhuang_jisuanqi.png"
          alt=""
          class="last_img"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Floor_weizhuang",
};
</script>

<style lang="less">
.Floor_weizhuang {
  padding-top: 50px;
  height: 800px;
  background-color: #ffffff;
  overflow: hidden;
  .weizhuang {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    .bottom_room {
      position: relative;
      width: 420px;
      margin-top: 50px;
      background-color: #fff;
      text-align: center;
      img {
        width: 100%;
        border-radius: 20px;
      }
      .first_img {
        position: absolute;
        top: 30px;
        left: -235px;
      }
      .last_img {
        position: absolute;
        top: 30px;
        right: -235px;
      }
      .other_img {
        position: relative;
        z-index: 99;
      }
    }

    .top_room {
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      justify-content: center;
      align-content: flex-start;
      width: 600px;
      padding-top: 40px;
      .weizhuang_icon {
        width: 400px;
        text-align: center;
        img {
          width: 96px;
          height: 96px;
        }
      }

      h1 {
        margin-top: 10px;
        font-size: 56px;
        font-weight: 400;
        color: #333;
      }
      h2 {
        width: 100%;
        margin-top: 10px;
        font-size: 27px;
        font-weight: 400;
        color: #666;
      }
    }
  }
}
</style>
