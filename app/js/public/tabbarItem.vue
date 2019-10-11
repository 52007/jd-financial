<template>
  <div class="tabbarItem"
       @click="clickTabbar">
    <div v-if="!isActive">
      <slot name="tabbarItem"></slot>
    </div>
    <div v-else>
      <slot name="tabbarItem-active"></slot>
    </div>
    <div :style="activeStyle">
      <slot name="tabbarText"></slot>
    </div>
  </div>
</template>

<script>
export default {
  name: 'tabbarItem',
  props: {
    path: String,
  },
  computed: {
    isActive () {
      return this.$route.path.indexOf(this.path) !== -1
    },
    activeStyle () {
      return this.isActive ? { color: '#4668FF' } : {}
    }
  },
  methods: {
    clickTabbar () {
      this.$router.push(this.path)
      console.log(this.$router)
      console.log(this.$route)
    }
  }

}
</script>

<style lang="scss">
@import "../../css/element.scss";
.tabbarItem {
  flex: 1;
  height: 49px;
  font-size: 22px;
  text-align: center;
  img {
    width: 44px;
    height: 44px;
    display: inline-block;
    margin: 12px auto 6px;
  }
}
</style>