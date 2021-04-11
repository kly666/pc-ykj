<template>
  <div class="menu">
    <div class="w menu_content">
      <div class="menu_text">
        <h1>异空间，真正隐藏守护你的数据文件</h1>
        <h2>多彩功能，丰富内容，享受你的数据隐私空间</h2>
      </div>
      <div class="menu_type">
        <div class="menu_type_box">
          <img src="~assets/img/menu_icon/wenben.svg" alt="" />
          <p>文本隐藏</p>
        </div>
        <div class="menu_type_box">
          <img src="~assets/img/menu_icon/tupian.svg" alt="" />
          <p>图像隐藏</p>
        </div>
        <div class="menu_type_box">
          <img src="~assets/img/menu_icon/yinpin.svg" alt="" />
          <p>音频隐藏</p>
        </div>
        <div class="menu_type_box">
          <img src="~assets/img/menu_icon/shiping.svg" alt="" />
          <p>视频隐藏</p>
        </div>
        <div class="menu_type_box">
          <img src="~assets/img/menu_icon/qita.svg" alt="" />
          <p>其它类型</p>
        </div>
        <div class="menu_type_box">
          <img src="~assets/img/menu_icon/huishou.svg" alt="" />
          <p>回收站</p>
        </div>
        <div class="menu_type_box">
          <img src="~assets/img/menu_icon/wenjian.svg" alt="" />
          <p>文件柜</p>
        </div>
        <div class="menu_type_box">
          <img src="~assets/img/menu_icon/jiesuo.svg" alt="" />
          <p>应用解锁</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Menu",
};
</script>

<style lang="less">
.menu {
  background-color: #f7f7f7;
  // height: 600px;
}
.menu_content {
  .menu_text {
    padding-top: 100px;
    text-align: center;
    h1 {
      font-size: 56px;
      color: #333;
    }
    h2 {
      margin-top: 20px;
      font-size: 27px;
      color: #666;
    }
  }
  .menu_type {
    margin-top: 100px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    .menu_type_box {
      width: 150px;
      height: 180px;
      padding: 20px;
      text-align: center;
      img {
        width: 120px;
      }
      p {
        margin-top: 5px;
      }
    }
  }
}
</style>