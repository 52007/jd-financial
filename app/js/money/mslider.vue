<template>
  <article>
    <slider :items="items"
            :cname="$style.slider">
    </slider>
  </article>
</template>

<script>
import slider from '../core/slider.vue'
export default {
  data () {
    return {
      items: [{
        href: 'home',
        src: '//img12.360buyimg.com/jrpmobile/jfs/t11149/181/856008463/68797/dc303e9/59f97baeN3cdae084.jpg?width=750&height=400'
      }, {
        hredf: 'home',
        src: '//img12.360buyimg.com/jrpmobile/jfs/t9994/205/2575467053/189117/125e7b05/59f97c36N7599be57.png?width=750&height=400'
      }]
    }
  },
  components: {
    slider
  }
}
</script>

<style lang="scss" module>
@import "../../css/element.scss";

.slider {
  margin-top: 100px;
  img {
    width: 100%;
  }
}
.list {
  @include list(row);
  background: #fff;
  padding-top: 40px;
  padding-bottom: 20px;
  justify-content: space-around;
  a {
    text-decoration: none;
  }
  .item {
    text-align: center;
    img {
      display: inline-block;
      width: 90px;
      height: 90px;
    }
    h4 {
      font-size: 26px;
      margin-top: 12px;
      color: #666;
    }
    &:nth-child(3) {
      h4 {
        color: #f00;
      }
    }
  }
}
</style>