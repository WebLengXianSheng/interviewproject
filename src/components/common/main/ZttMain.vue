<template>
  <div class="z-main">
    <div class="z-bg"></div>
    <div class="z-main-center">
      <div class="z-blank"></div>
      <ztt-search></ztt-search>
      <ztt-main-nav></ztt-main-nav>
      <ztt-content></ztt-content>
      <ztt-layer></ztt-layer>
      <ztt-layer-goods></ztt-layer-goods>
      <ztt-layer-ad></ztt-layer-ad>
      <ztt-layer-shop></ztt-layer-shop>
      <ztt-layer-fashion></ztt-layer-fashion>
      <ztt-layer-sale></ztt-layer-sale>
      <ztt-layer-hot-sale></ztt-layer-hot-sale>
      <ztt-layer-helper></ztt-layer-helper>
      
    </div>
  </div>
</template>

<script>
import ZttSearch from "components/common/main/ZttSearch"
import ZttMainNav from "components/common/main/ZttMainNav"

import ZttContent from "components/common/main/content/ZttContent"
import ZttLayer from "components/common/main/layer/ZttLayer"
import ZttLayerGoods from "components/common/main/layer/ZttLayerGoods"
import ZttLayerAd from "components/common/main/layer/ZttLayerAd"
import ZttLayerShop from "components/common/main/layer/ZttLayerShop"
import ZttLayerFashion from "components/common/main/layer/ZttLayerFashion"
import ZttLayerSale from "components/common/main/layer/ZttLayerSale"
import ZttLayerHotSale from "components/common/main/layer/ZttLayerHotSale"
import ZttLayerHelper from "components/common/main/layer/ZttLayerHelper"

export default {
  name:"ZttMain",
  components:{
    ZttSearch,
    ZttMainNav,
    ZttContent,
    ZttLayer,
    ZttLayerGoods,
    ZttLayerAd,
    ZttLayerShop,
    ZttLayerFashion,
    ZttLayerSale,
    ZttLayerHotSale,
    ZttLayerHelper,
  }
}
</script>

<style scoped>
.z-blank{
  position: absolute;
  width: 1200px;
  height: 19px;
}
.z-bg{
  position: absolute;
  z-index: 0;
  width: 1902px;
  height: 140px;
  background: white;
}

</style>