<template>
  <div class="header_fix">
    <div class="header_bar container">
    <!-- <img class="header_logo" src="http://p8.qhimg.com/t01b0ed1254c8390ccb.png"> -->
    <el-row >
      <el-col :span="6">
        <div class="header_height">
           <img class="header_logo" src="http://p8.qhimg.com/t01b0ed1254c8390ccb.png">
        </div>
      </el-col>
      <el-col :span="6">
        <div class="header_height ">
          <el-row>
            <el-col :span="6"><a class="header_tag">首页</a></el-col>
            <el-col :span="6"><a class="header_tag">产品</a></el-col>
            <el-col :span="12"><a class="header_tag">DNS安全研究</a></el-col>
          </el-row>
        </div>
      </el-col>
      <el-col :span="12">
        <div class="header_height "></div>
      </el-col>
    </el-row>
  </div>
  </div>
</template>
<script>
export default {
  name: 'Header'
}
</script>