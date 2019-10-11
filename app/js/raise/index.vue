<template lang="html">
    <div>
      <Heador></Heador>
      <Rslider></Rslider>
      <Sign></Sign>
      <In></In>
      <More></More>
      <Footor cname="mfooter"></Footor>
      <!-- <Navbar></Navbar> -->
      <MainTabbar></MainTabbar>
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Rslider from './rslider.vue'
import Sign from './sign.vue'
import In from './in.vue'
import More from './more.vue'
import Footor from '../public/footer.vue'
import Navbar from '../public/navbar.vue'
import MainTabbar from '../public/mainTabbar.vue'
export default {
  components: {
    Heador,
    Rslider,
    Sign,
    In,
    More,
    Footor,
    Navbar,
    MainTabbar
  }
}
</script>

<style lang="scss">
@import "../../css/reset.scss";
.mfooter {
  margin-top: 0 !important;
  ul {
    li:first-child {
      display: none;
    }
  }
}
</style>
