<template>
  <div id="app">
    <Header />
    <Main />
    <Floor_multi_type />
    <Floor_all_type />
    <Floor_mimaben />

    <Floor_xiutan />
    <Floor_weizhuang />
    <Floor_huishou />
    <Floor_jiami />
    <Menu />
    <page-download />
    <Footer />
  </div>
</template>

<script>
import Header from "views/header/Header";
import Main from "views/main/Main";
import Floor_all_type from "views/floor/Floor_all_type";
import Floor_multi_type from "views/floor/Floor_multi_type";
import Floor_huishou from "views/floor/Floor_huishou";
import Floor_xiutan from "views/floor/Floor_xiutan";
import Floor_jiami from "views/floor/Floor_jiami";
import Menu from "views/floor/Menu";
import Footer from "views/footer/Footer";
import PageDownload from "views/pageDownload/PageDownload";
import Floor_weizhuang from "views/floor/Floor_weizhuang";
import Floor_mimaben from "views/floor/Floor_mimaben";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Floor_all_type,
    Floor_huishou,
    Floor_multi_type,
    Floor_weizhuang,
    Floor_xiutan,
    Floor_jiami,
    Floor_mimaben,
    PageDownload,
    Menu,
    Footer,
  },
};
</script>

<style>
@import "assets/css/base.css";
.w {
  width: 1000px;
  margin: 0 auto;
}
</style>
