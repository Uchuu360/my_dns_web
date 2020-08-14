<template>
  <div class="banner_height">
    <div class="banner_bg" style="padding-top:5%">
      <el-row>
        <el-col :span="6">
          <bannerTitle></bannerTitle>
        </el-col>
        <el-col :span="12">
          <div class="banner_height">
            <img class="banner_img" src="https://p4.ssl.qhimg.com/t0183035d56494abe04.png">
          </div>
        </el-col>
        <el-col :span="6">
          <div class="banner_height">
            <bannerTitle></bannerTitle>
          </div>
        </el-col>
      </el-row>
    </div>
  </div>
</template>


<script>
import BannerTitle from './home_tiny_cpn/bannerTitle'
export default {
  name: "Banner",
  components:{
    bannerTitle:BannerTitle
  }
}
</script>