<template>
  <div id="nav">
    <router-view>
      <!-- <keep-alive>
        <component :is="Component"></component>
      </keep-alive> -->
    </router-view>

    <van-tabbar route>
      <van-tabbar-item to="/" icon="home-o">首页</van-tabbar-item>
      <van-tabbar-item to="/mine" icon="orders-o">课程页</van-tabbar-item>
      <van-tabbar-item to="/profile" icon="manager-o">个人中心</van-tabbar-item>
    </van-tabbar>
  </div>
  <router-view/>
</template>

<style lang="scss">
</style>
