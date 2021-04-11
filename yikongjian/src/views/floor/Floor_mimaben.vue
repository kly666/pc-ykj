<template>
  <div class="floor_mimaben">
    <div class="w mimaben">
      <div class="top_room">
        <div class="mimaben_icon">
          <img src="~assets/img/icon/mimaben_icon.svg" alt="" />
        </div>
        <h1>密码本</h1>
        <h2>安全保存每一个密码</h2>
      </div>
      <div class="bottom_room">
        <img src="~assets/img/images/mimaben1.png" alt="" class="first_img" />
        <img src="~assets/img/images/mimaben2.png" alt="" class="other_img" />
        <img src="~assets/img/images/mimaben3.png" alt="" class="last_img" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Floor_multi_type",
};
</script>

<style lang="less">
.floor_mimaben {
  padding-top: 50px;
  height: 800px;
  background-color: #ffffff;
  overflow: hidden;
  .mimaben {
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
      .mimaben_icon {
        width: 400px;
        text-align: center;
        img {
          width: 96px;
          height: 96px;
        }
      }

      h1 {
        text-align: center;
        width: 100%;
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
