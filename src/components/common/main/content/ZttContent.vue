<template>
<div class="z-main-content">
  <div class="z-content">
    <ztt-content-left></ztt-content-left>
    <ztt-content-center></ztt-content-center>
    <ztt-content-right></ztt-content-right>
  </div>
</div>
</template>

<script>
import ZttContentLeft from "components/common/main/content/ZttContentLeft"
import ZttContentCenter from "components/common/main/content/ZttContentCenter"
import ZttContentRight from "components/common/main/content/ZttContentRight"

export default {
  name:"ZttContent",
  components:{
    ZttContentLeft,
    ZttContentCenter,
    ZttContentRight
  }
}
</script>

<style scoped>
  .z-main-content{
  width: 1190px;
  height: 540px;
  }
  .z-content{
    position: absolute;
    width: 1190px;
    height: 522px;
  }

</style>