<template lang="html">
    <div>
      <Heador></Heador>
      <Mslider></Mslider>
      <Ada></Ada>
      <Money></Money>
      <Adb></Adb>
      <Finance></Finance>
      <Adc></Adc>
      <Footor cname="mfooter"></Footor>
      <!-- <Navbar></Navbar> -->
      <MainTabbar></MainTabbar>
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Mslider from './mslider.vue'
import Ada from './ada.vue'
import Money from './money.vue'
import Adb from './adb.vue'
import Finance from './finance.vue'
import Adc from './adc.vue'
import Footor from '../public/footer.vue'
import Navbar from '../public/navbar.vue'
import MainTabbar from '../public/mainTabbar.vue'
export default {
  components: {
    Heador,
    Mslider,
    Ada,
    Money,
    Adb,
    Finance,
    Adc,
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
