<template>
  <div>
    <el-carousel height="690px">
      <el-carousel-item v-for="item in 1" :key="item" class="banner_height">
        <vueBanner></vueBanner>
      </el-carousel-item>
    </el-carousel>
  </div>
</template>


<script>
import Banner from './banner'
export default {
  name: "Swiper",
  components:{
    vueBanner: Banner,
  }
}
</script>