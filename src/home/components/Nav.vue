<template>
<div>
    <div class="outnav">
        <ul class="nav cleaerfix">
            <li class="category first"><a href="" class="title">产品分类</a></li>
            <li class="first"><a href="" class="title">首页</a></li>
            <li class="first"><a href="" class="title">服务平台</a></li>
            <li class="first"><a href="" class="title">技术支持</a></li>
            <li class="first"><a href="" class="title">充值平台</a></li>
            <li class="first"><a href="" class="title">关于我们</a></li>
        </ul>
    </div>
</div>
</template>

<script>
export default {
  name: 'HomeNav',

}
</script>
<style lang="stylus" scoped>
  .outnav
    width: 1366px;
    margin 15px auto 0 auto;
    background: #404144;
    height: 50px;
    line-height: 50px;
    vertical-align: middle;
    .nav
        display: block;
        -webkit-margin-before: 1em;
        -webkit-margin-after: 1em;
        -webkit-margin-start: 0px;
        -webkit-margin-end: 0px;
        .category
            width 225px
            padding 0
            background #ff4a00
        .first
            float: left;
            height: 50px;
            line-height: 50px;
            vertical-align: middle;
            padding-left 100px
            .title
                display inline-block
                font-size 16px
                font-weight normal
                color: #fff
</style>

