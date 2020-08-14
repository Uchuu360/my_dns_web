<template>
  <div id="app">
    <el-container style="height: 5000px; background-color: white;">
      <el-header style="height:80px"
                 class="header_height">
        <vueHeader class="header_bg"></vueHeader>
      </el-header>
      <el-main>
        <div class="container">
          <vueSwiper></vueSwiper>
          <homeTab></homeTab>
        </div>
      </el-main>
      <el-footer style="background-color:blue">footer</el-footer>
    </el-container>
  </div>
</template>

<script>
import Header from './Header'

import Swiper from './swiper'

import HomeTab from './homeTab'

export default {
  name: 'Home',
  components: {
    vueHeader: Header,
    vueSwiper: Swiper,
    homeTab: HomeTab
  }
}
</script>

