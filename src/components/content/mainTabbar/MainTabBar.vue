<template>
<div>
  <tab-bar>
    <tab-bar-item link="/home" active-color="#d4237a">
      <img slot="item-icon" src="@/assets/img/tabbar/homepage.svg" alt="">
      <img slot="item-icon-active" src="@/assets/img/tabbar/homepage_active.svg" alt="">
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item link="/category" active-color="#d4237a">
      <img slot="item-icon" src="@/assets/img/tabbar/sort.svg" alt="">
      <img slot="item-icon-active" src="@/assets/img/tabbar/sort_active.svg" alt="">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item link="/cart" active-color="#d4237a">
      <img slot="item-icon" src="@/assets/img/tabbar/shoppingcart.svg" alt="">
      <img slot="item-icon-active" src="@/assets/img/tabbar/shoppingcart_active.svg" alt="">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item link="/profile" active-color="#d4237a">
      <img slot="item-icon" src="@/assets/img/tabbar/profile.svg" alt="">
      <img slot="item-icon-active" src="@/assets/img/tabbar/profile_active.svg" alt="">
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</div>
</template>

<script>
import TabBar from "@/components/common/tabbar/TabBar";
import TabBarItem from "@/components/common/tabbar/TabBarItem";

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
