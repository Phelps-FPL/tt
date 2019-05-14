<template>
<div>
  <div class="top">
    <div class="innerCon clearfix">
      <div class="left hidden">欢迎您的到来</div>
      <div class="right">
        <el-link href="https://element.eleme.io" target="_blank">English</el-link>
        <strong>|</strong>
        <el-link href="https://element.eleme.io" target="_blank">设为首页</el-link>
        <strong>|</strong>
        <el-link href="https://element.eleme.io" target="_blank">收藏</el-link>
      </div>
    </div>
  </div>
  <div class="logoCon">
    <a href="#" ><img src="/static/logo.jpg" alt="拓途"></a>
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
    width: 1500px
    margin: 0 auto
    .left
      float left
    .right
      float right 
      margin-right 40px
      // fonsz 32px     
  .logoCon
    margin 20px auto 0 auto
    padding-left 40px
    width 1326px
</style>

