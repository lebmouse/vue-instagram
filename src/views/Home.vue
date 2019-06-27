<template>
  <div class="home">
    <home-toolbar></home-toolbar>
    <the-bottom></the-bottom>
  </div>
</template>

<script>
// @ is an alias to /src
import TheBottom from "@/components/TheBottom";
import HomeToolbar from "@/components/ToolBar/HomeToolbar";

export default {
  name: "home",
  components: {
    TheBottom,
    HomeToolbar
  }
};
</script>
