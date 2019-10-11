<template lang="html">
    <div :class="$style.home">
      <Heador></Heador>
      <Hslider></Hslider>
      <Novice></Novice>
      <Borrow></Borrow>
      <Money></Money>
      <Product></Product>
      <Life></Life>
      <Footor></Footor>
      <!-- <Navbar></Navbar> -->
      <MainTabbar></MainTabbar>
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Hslider from './hslider.vue'
import Novice from './novice.vue'
import Borrow from './borrow.vue'
import Money from './money.vue'
import Product from './product.vue'
import Life from './life.vue'
import Footor from '../public/footer.vue'
import Navbar from '../public/navbar.vue'
import MainTabbar from '../public/mainTabbar.vue'
export default {
  components: {
    Heador,
    Hslider,
    Novice,
    Borrow,
    Money,
    Product,
    Life,
    Footor,
    Navbar,
    MainTabbar
  }
}
</script>

<style lang="scss" module>
@import "../../css/reset.scss";
</style>
