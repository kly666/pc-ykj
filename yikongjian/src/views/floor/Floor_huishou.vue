<template>
  <div class="floor">
    <div class="w huishou">
      <div class="left_room">
        <img src="~assets/img/images/huishou.png" alt="" />
      </div>
      <div class="right_room">
        <div class="huishou_icon">
          <img src="~assets/img/icon/huishou_icon.svg" alt="" />
        </div>
        <h1>回收站</h1>
        <h2>保存并恢复误删除的文件</h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Floor_huishou",
};
</script>

<style lang="less">
.floor {
  padding-top: 100px;
  height: 500px;
  background-color: #f7f7f7;
  overflow: hidden;
  .huishou {
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

      .huishou_icon {
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
