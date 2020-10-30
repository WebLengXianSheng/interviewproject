<template>
  <div class="z-main-nav">
    <h2>主题市场</h2>
    <div class="z-main-nav-right">
      <ul>
        <li>
          <a v-for="item in alist1" href="#">{{ item }}</a>
        </li>
      </ul>
      <ul>
        <li>|</li>
        <li>
          <a v-for="item in alist2" href="#">{{ item }}</a>
        </li>
      </ul>
      <ul>
        <li>|</li>
        <li>
          <a v-for="item in alist3" href="#">{{ item }}</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "ZttMainNav",
  data() {
    return {
      alist1: ["天猫", "聚划算", "天猫超市"],
      alist2: ["淘抢购", "电器城", "司法拍卖", "淘宝心选"],
      alist3: ["飞猪旅行", "智能生活", "苏宁易购"]
    };
  }
};
</script>

<style scoped>
.z-main-nav {
  height: 30px;
  line-height: 30px;
  color: white;
}
.z-main-nav-right{
  max-width: 1200px;
  height: 30px;
  color: #fff;
  background: linear-gradient(to right, #fc8813, #fc5412);
}
.z-main-nav-right a{
  color: #fff;
  font-size: 16px;
}
.z-main-nav h2 {
  float: left;
  width: 190px;
  margin: 0;
  padding: 0;
  text-align: center;
  background: #fc5412;
  font-size: 14px;
}
.z-main-nav ul {
  float: left;
}
.z-main-nav li{
  margin: 0 3px;
  padding: 0 4px;
}
</style>
