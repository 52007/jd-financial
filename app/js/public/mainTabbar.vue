<template>
  <div>
    <Tabbar>
      <TabbarItem path="/home">
        <img slot="tabbarItem"
             src="//img12.360buyimg.com/jrpmobile/jfs/t1/8536/31/4338/935/5bda5c27Ef3510bb3/d92a8259c237d16b.png?width=60&height=60"
             alt="">
        <img slot="tabbarItem-active"
             src="//img12.360buyimg.com/jrpmobile/jfs/t1/8325/8/4331/3095/5bda5c89E1be47c14/47b6a296683a12a5.png?width=90&height=90"
             alt="">
        <div slot="tabbarText">首页</div>
      </TabbarItem>
      <TabbarItem path="/money">
        <img slot="tabbarItem"
             src="//img12.360buyimg.com/jrpmobile/jfs/t1/1890/15/14183/1269/5bda5c97E34734b01/241a0f5b17fd3e51.png?width=60&height=60"
             alt="">
        <img slot="tabbarItem-active"
             src="//img12.360buyimg.com/jrpmobile/jfs/t1/8325/8/4331/3095/5bda5c89E1be47c14/47b6a296683a12a5.png?width=90&height=90"
             alt="">
        <div slot="tabbarText">理财</div>
      </TabbarItem>
      <TabbarItem path="/ious">
        <img slot="tabbarItem"
             src="//img12.360buyimg.com/jrpmobile/jfs/t1/5291/40/14133/594/5bda5ca3E92d0e800/09ac81fa5a5c96ef.png?width=60&height=60"
             alt="">
        <img slot="tabbarItem-active"
             src="//img12.360buyimg.com/jrpmobile/jfs/t1/8325/8/4331/3095/5bda5c89E1be47c14/47b6a296683a12a5.png?width=90&height=90"
             alt="">
        <div slot="tabbarText">白条</div>
      </TabbarItem>
      <TabbarItem path="/raise">
        <img slot="tabbarItem"
             src="//img12.360buyimg.com/jrpmobile/jfs/t1/3358/38/14064/816/5bda5cabEcb7eca8b/9bb064f1cda7ceba.png?width=60&height=60"
             alt="">
        <img slot="tabbarItem-active"
             src="//img12.360buyimg.com/jrpmobile/jfs/t1/8325/8/4331/3095/5bda5c89E1be47c14/47b6a296683a12a5.png?width=90&height=90"
             alt="">
        <div slot="tabbarText">众筹</div>
      </TabbarItem>
    </Tabbar>
  </div>
</template>

<script>
import Tabbar from './tabbar'
import TabbarItem from './tabbarItem'
export default {
  components: {
    Tabbar,
    TabbarItem
  }
}
</script>

<style>
</style>