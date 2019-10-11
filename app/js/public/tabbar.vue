<template>
  <div class="tabbar">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'tabbar'
}
</script>

<style lang="scss">
@import "../../css/element.scss";
.tabbar {
  display: flex;
  background: #fff;
  height: 100px;
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
}
</style>