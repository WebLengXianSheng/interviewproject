<template>
  <div id="app">
    <ztt-nav></ztt-nav>
    <ztt-nav-ad></ztt-nav-ad>
    <ztt-main></ztt-main>
    <ztt-footer></ztt-footer>
  </div>
</template>

<script>
import ZttNav from "components/common/nav/ZttNav"
import ZttNavAd from "components/common/nav/ZttNavAd"
import ZttMain from "components/common/main/ZttMain"
import ZttFooter from "components/common/footer/ZttFooter"

export default {
  name: "App",
  data() {
    return {
      
    }
  },
  components: {
    ZttNav,
    ZttNavAd,
    ZttMain,
    ZttFooter
  }
};
</script>

<style>
@import "./assets/css/base.css";

</style>
