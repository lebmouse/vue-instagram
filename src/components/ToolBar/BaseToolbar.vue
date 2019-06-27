<template>
  <nav class="BaseToolbar">
    <div class="BaseToolbar-Group flexbox__between">
      <slot class="flexitem"></slot>
    </div>
  </nav>
</template>

<script>
export default {
  name: "BaseToolbar"
};
</script>

<style lang='scss' scoped>
@import "@/assets/css/index.scss";

.BaseToolbar {
  // position
  position: absolute;
  top: 0;
  // size
  width: 100%;
  // box-model
  border-bottom: 1px solid $border-color;
  // content
  background-color: $basic-bg-color;
  &-Group {
    // box-model
    padding: 0px 16px;
    // size
    height: 44px;
    // font
    font-size: 24px;
  }
}
</style>