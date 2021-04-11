<template>
  <div class="floor">
    <div class="w all_type">
      <div class="left_room">
        <img src="~assets/img/all_type.png" alt="" />
      </div>
      <div class="right_room">
        <div class="all_type_icon">
          <img src="~assets/img/all_type_icon.png" alt="" />
        </div>
        <h1>全格式支持</h1>
        <h2>给你的私密文件一个最隐秘的空间</h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Floor",
};
</script>

<style lang="less">
.floor {
  padding-top: 100px;
  height: 500px;
  background-color: #f7f7f7;
  overflow: hidden;
  .all_type {
    display: flex;
    justify-content: space-around;

    .left_room {
      width: 420px;
      background-color: #efefef;
      text-align: center;
      img {
        width: 70%;
        box-shadow: 5px 0 2px rgba(119, 115, 115, 0.5);
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
