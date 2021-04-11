<template>
  <div class="floor_multi_type">
    <div class="w multi_type">
      <div class="top_room">
        <div class="all_type_icon">
          <img src="~assets/img/icon/show_icon.svg" alt="" />
        </div>
        <h1>数据类别展示</h1>
        <h2>让你的每一种私密文件得到安全保护</h2>
      </div>
      <div class="bottom_room">
        <img
          src="~assets/img/images/show_xiangce.png"
          alt=""
          class="first_img"
        />
        <img
          src="~assets/img/images/show_wenjiangui.png"
          alt=""
          class="other_img"
        />
        <img src="~assets/img/images/show_shipin.png" alt="" class="last_img" />
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
.floor_multi_type {
  padding-top: 50px;
  height: 800px;
  background-color: #ffffff;
  overflow: hidden;
  .multi_type {
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
      .all_type_icon {
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
