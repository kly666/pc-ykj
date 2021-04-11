<template>
  <div class="floor_xiutan">
    <div class="w xiutan">
      <div class="right_room">
        <div class="xiutan_icon">
          <img src="~assets/img/icon/jinzi_icon.svg" alt="" />
        </div>
        <h1>文件防嗅探</h1>
        <h2>防止文件被非法应用/网站嗅探</h2>
      </div>
      <div class="left_room">
        <img src="~assets/img/images/xiutan.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Floor_xiutan",
};
</script>

<style lang="less">
.floor_xiutan {
  padding-top: 100px;
  height: 500px;
  background-color: #f7f7f7;
  overflow: hidden;
  .xiutan {
    display: flex;
    justify-content: space-around;

    .left_room {
      margin-top: -70px;
      width: 420px;
      border-radius: 20px;
      text-align: center;
      img {
        width: 100%;
        border-radius: 20px;
      }
    }
    .right_room {
      display: flex;
      flex-direction: row;
      justify-content: center;
      flex-wrap: wrap;
      align-content: flex-start;
      width: 420px;
      padding-top: 80px;

      .xiutan_icon {
        width: 400px;
        text-align: center;
        img {
          background:  url(~assets/img/icon/xiutan_icon2.svg) no-repeat;
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
