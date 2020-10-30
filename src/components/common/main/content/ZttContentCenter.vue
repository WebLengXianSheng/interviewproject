<template>
  <div class="z-content-center">
    <div class="z-content-center-left"></div>
    <div class="z-content-center-right"></div>
  </div>
</template>

<script>
export default {
  name:"ZttContentCenter"
}
</script>

<style scoped>
  .z-content-center{
    float: left;
    width: 710px;
    height: 522px;
  }
  .z-content-center-left{
    margin-left: 10px;
    margin-top: 10px;
    float: left;
    height: 512px;
    width: 520px;
    background: white;
  }
  .z-content-center-right{
    float: right;
    width: 160px;
    height: 512px;
    margin-right: 10px;
    margin-top: 10px;
    background: white;
    
  }
</style>