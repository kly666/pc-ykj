<template>
  <div class="Floor_jiami">
    <div class="w jiami">
      <div class="top_room">
        <div class="jiami_icon">
          <img src="~assets/img/icon/jiami_icon.svg" alt="" />
        </div>
        <h1>应用加密</h1>
        <h2>使用指纹/手势密码/数字密码进入本应用</h2>
      </div>
      <div class="bottom_room">
        <img
          src="~assets/img/images/jiami_shoushi.png"
          alt=""
          class="first_img"
        />
        <img
          src="~assets/img/images/jiami_zhiwen.png"
          alt=""
          class="other_img"
        />
        <img src="~assets/img/images/jiami_shuzi.png" alt="" class="last_img" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Floor_jiami",
};
</script>

<style lang="less">
.Floor_jiami {
  padding-top: 50px;
  height: 800px;
  background-color: #ffffff;
  overflow: hidden;
  .jiami {
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
      justify-content: center;
      flex-wrap: wrap;
      align-content: flex-start;
      width: 500px;
      padding-top: 40px;
      .jiami_icon {
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
        margin-top: 10px;
        font-size: 27px;
        font-weight: 400;
        color: #666;
      }
    }
  }
}
</style>
