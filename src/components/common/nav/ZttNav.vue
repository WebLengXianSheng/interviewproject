<template>
  <div class="ztt-nav">
    <header>
      <div class="z-nav">
        <div class="z-nav-left">
          <ul>
            <li><a class="loca" href="#">中国大陆<i class="down-arrow"></i></a></li>
            <li v-for="item in alist"><a href="#">{{item}}</a></li>
          </ul>
        </div>
        <div class="z-nav-right">
          <ul>
            <li v-for="item in alist2"><a href="#">{{item}}</a></li>
          </ul>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "ZttNav",
  data(){
    return{
      alist:[
        '亲，请登录',
        '免费注册',
        '手机逛淘宝'
      ],
      alist2:[
        '我的淘宝',
        '购物车',
        '收藏夹',
        '商品分类',
        '免费开店',
        '千牛卖家中心',
        '联系客服',
        '网站导航',
      ]
    }
    
  }
};
</script>

<style scoped>

</style>
