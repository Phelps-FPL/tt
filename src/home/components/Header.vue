<template>
  <div class="top">
    <div class="innerCon clearfix">
      <div class="left hidden">欢迎您的到来</div>
      <div class="right">
        <el-link href="https://element.eleme.io" target="_blank">English</el-link>
        <el-link href="https://element.eleme.io" target="_blank">设为首页</el-link>
        <strong>|</strong>
        <el-link href="https://element.eleme.io" target="_blank">收藏</el-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader',

}
</script>
<style lang="stylus" scoped>
  .top >>> .el-link
    vertical-align baseline
  .top
    height: 36px
    line-height: 36px
    vertical-align: middle
    border-bottom: 1px solid #dfdfdf
    width: 1366px
    margin: 0 auto
    .left
      float left
    .right
      float right 
      // fonsz 32px
      
</style>

