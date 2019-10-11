<template>
  <Panel title="金融头条"
         :class="$style.panel">
    <section :class="$style.content">
      <swiper :options="options">
        <swiper-slide>百万白条券免费送，速来领取！！<em>></em></swiper-slide>
        <swiper-slide>签到领流量，1元500M！<em>></em></swiper-slide>
      </swiper>
    </section>
  </Panel>
</template>

<script>
import Panel from '../core/panel.vue'
import { swiper, swiperSlide } from 'vue-awesome-swiper'
export default {
  components: {
    Panel,
    swiper,
    swiperSlide
  },
  data () {
    return {
      options: {
        autoplay: true,
        loop: true,
        direction: 'vertical',
      }
    }
  }
}
</script>

<style lang="scss">
.swiper-container-vertical {
  height: 72px;
  .swiper-slide {
    font-size: 26px;
    font-family: PingFangSC-Medium;
    font-weight: 700;
    color: #333;
  }
}
</style>

<style lang="scss" module>
@import "../../css/element.scss";
.panel {
  @include panel;
  > h4 {
    display: none;
  }
  margin-top: 100px !important;
  margin-bottom: 0 !important;
  .content {
    height: 72px;
    line-height: 72px;
    overflow: hidden;
    background: url(//m.jr.jd.com/spe/qyy/main/images/scroll_title_img.png) left
      top no-repeat;
    background-size: auto 100%;
    padding-left: 170px;
    em {
      font-size: 30px;
      color: #ddd;
      float: right;
      margin-right: 20px;
    }
  }
}
</style>