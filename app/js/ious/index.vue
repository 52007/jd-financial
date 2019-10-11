<template lang="html">
    <div>
      <Heador></Heador>
      <Islider></Islider>
      <Welfare></Welfare>
      <More></More>
      <Footor></Footor>
      <!-- <Navbar></Navbar> -->
      <MainTabbar></MainTabbar>
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Islider from './islider.vue'
import Welfare from './welfare.vue'
import More from './more.vue'
import Footor from '../public/footer.vue'
import Navbar from '../public/navbar.vue'
import MainTabbar from '../public/mainTabbar.vue'
export default {
  components: {
    Heador,
    Islider,
    Welfare,
    More,
    Footor,
    Navbar,
    MainTabbar
  }
}
</script>

<style lang="scss">
@import "../../css/reset.scss";
</style>
