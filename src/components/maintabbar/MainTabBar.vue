<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="blue">
      <img slot="item-icon" src="@/assets/img/tabbar/shouye.svg" alt="">
      <img slot="item-active" src="@/assets/img/tabbar/chuanshu.svg" alt="">
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="blue">
      <img slot="item-icon" src="@/assets/img/tabbar/fenlei.svg" alt="">
      <img slot="item-active" src="@/assets/img/tabbar/chuanshu.svg" alt="">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart" activeColor="blue">
      <img slot="item-icon" src="@/assets/img/tabbar/gouwuche.svg" alt="">
      <img slot="item-active" src="@/assets/img/tabbar/chuanshu.svg" alt="">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="blue">
      <img slot="item-icon" src="@/assets/img/tabbar/wode.svg" alt="">
      <img slot="item-active" src="@/assets/img/tabbar/chuanshu.svg" alt="">
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
import TabBar from "@/components/tabbar/TabBar";
import TabBarItem from "@/components/tabbar/TabBarItem";

export default {
  name: "MainTabBar",
  components: {
    TabBar,
    TabBarItem
  }
}
</script>

<style scoped>

</style>