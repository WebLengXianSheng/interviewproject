<template>
<div class="z-search">
  <div class="z-search-logo">
    <img :src="goUrl">
  </div>
  <div class="z-search-main">
    <img :src="searchUrl" alt="">
  </div>
</div>
</template>

<script>
export default {
  name:"ZttSearch",
  data(){
    return{
      goUrl:require("../../../assets/img/logo.gif"),
      searchUrl:require("../../../assets/img/search.jpg")
    }
    
  }
}
</script>

<style scoped>
.z-search{
  position: relative;
  z-index: 1;
  height: 121px;
  margin-top: 19px;
}
.z-search-logo{
  float: left;
  width: 190px;
  height: 121px;
  margin-top: -19px;
}
.z-search-main{
  float: left;
  width: 630px;
  height: 87px;
  margin-left: 68px;
  margin-top: 19px;
}
</style>