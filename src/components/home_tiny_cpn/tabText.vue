<template>
  <div class="home_tabcontent">
    <div>
      <h3 class="home_tabcontent_title_text" name="title"><slot>360公共DNS</slot></h3>
      <div class="home_tabcontent_title_text_des"><slot name="title_des">针对政府、企业和个人用户的高速、安全、免费的公共DNS递归解析服务</slot></div>
    </div>
    <div v-for="(item,index) in textList " :key="index">
      <div>
        {{item.description}}
        <div>
          <img :src='item.url'>
          <span>{{item.title}}</span>
        </div>
        <div>
          <ul>
            <li v-for="(detail,i) in item.descrition" :key="i">
              {{detail}}
            </li>
          </ul>
        </div>
      </div>
    </div>
    <div>btn</div>
  </div>
  
</template>

<script>



export default {
  name: "tabText",
  props:['textList']
}
</script>