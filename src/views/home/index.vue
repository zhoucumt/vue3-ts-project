<template>
  <div class="home">
    <!-- 首页头部 -->
    <HomeHeader></HomeHeader>

    <!-- 轮播图 -->
    <HomeSwiper></HomeSwiper>

    <!-- 课程列表 -->
    <HomeList></HomeList>
  </div>
</template>

<script lang="ts">
import { defineComponent, computed, onMounted, ref } from 'vue';
import HomeHeader from './home-header.vue';
import HomeList from './home-list.vue';
import HomeSwiper from './home-swiper.vue';
// 专门为修改分类使用的options api

export default defineComponent({
  name: 'index',
  components: {
    HomeHeader,
    HomeList,
    HomeSwiper
  },
  setup() {
  }
});
</script>

<style lang="scss">

</style>
