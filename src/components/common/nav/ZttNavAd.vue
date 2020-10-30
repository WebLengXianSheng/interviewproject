<template>
  <div class="z-nav-ad">
    <div class="z-nav-ad-content">
      <img :src="navadUrl">
    </div>
  </div>
</template>

<script>
export default {
  name: "ZttNavAd",
  data(){
    return {
      navadUrl:require("assets/img/navad.jpg")
    }
  }
};
</script>

<style scoped>

</style>
