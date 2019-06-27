<template>
  <base-toolbar>
    <i class="fab fa-instagram navBtn"></i>
    <img class="BaseToolbar-logo" src="@/assets/img/logo_char.png" alt>
    <i class="fas fa-location-arrow"></i>
  </base-toolbar>
</template>

<script>
import BaseToolbar from "./BaseToolbar";
export default {
  name: "HomeToolbar",
  components: {
    "base-toolbar": BaseToolbar
  }
};
</script>

<style lang='scss' scoped>
@import "@/assets/css/index.scss";

.BaseToolbar{
  &-logo{
    height:30px;
  }
}
</style>
