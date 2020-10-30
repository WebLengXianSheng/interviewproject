<template>
  <div class="z-layer">
    <ul>
      <li><img :src="layerUrl1"></li>
      <li><img :src="layerUrl2"></li>
      <li><img :src="layerUrl3"></li>
      <li><img :src="layerUrl4"></li>
      <li><img :src="layerUrl5"></li>
    </ul>
  </div>
</template>

<script>
export default {
  name:"ZttLayer",
  data() {
    return {
      layerUrl1:require("assets/img/layer/layer1.png"),
      layerUrl2:require("assets/img/layer/layer2.png"),
      layerUrl3:require("assets/img/layer/layer3.png"),
      layerUrl4:require("assets/img/layer/layer4.png"),
      layerUrl5:require("assets/img/layer/layer5.png"),
    }
  }
}
</script>

<style scoped>
  .z-layer{
    width: 1190px;
    height: 92px;
    margin: 0 auto;
  }
  .z-layer li{
    float: left;
    width: 234px;
    height: 92px;
    margin: 0 2px;
    position: relative;
    background-size: cover;
  }
</style>