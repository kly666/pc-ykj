<template>
  <div id="header" class="shortcut">
    <div class="w">
      <div class="logo">
        <div>
          <a href="/"><img src="~assets/img/logo.png" alt="" /> 异空间</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>
<style>
.shortcut {
  height: 60px;
  line-height: 60px;
  background-color: #fff;
}
.logo {
  padding-left: 30px;
}
.logo img {
  width: 35px;
  vertical-align: middle;
}
.logo a {
  display: inline-block;
  font-size: 20px;
  font-weight: 700;
}
/* .logo a:hover {
  text-decoration: none;
} */
</style>