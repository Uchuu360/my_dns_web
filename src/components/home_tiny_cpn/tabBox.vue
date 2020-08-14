<template>
  <ul  class="home_tabwarp">
    <box>360公共DNS</box>
    <box>360DNS安全监测系统（SaaS版）</box>
    <box>360DNS安全监测系统（私有化部署版）</box>
    <li class="tab_movement"></li>
  </ul>

</template>

<script>
import box from './box'

export default {
  name: "TabBox",
  components:{
    box
  }
}
</script>