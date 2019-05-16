<template>
<div>
    <div class="bottom">
        <div class="innerCon">
            <ul class="clearfix">
                <li>
                    <h2><span>相关链接</span></h2>
                    <p> <a href="">云狗在线</a> </p>
                    <p><a href="">云导航</a> </p>
                    <p> <a href="">预警仪充警平台</a></p>
                </li>
                <li>
                    <h2><span>关注我们</span> </h2>
                    <p><a href="">公司介绍</a> </p>
                    <p> <a href="">官方微信</a></p>
                    <p> <a href="">腾讯微博</a></p>
                </li>
                <li>
                    <h2><span>下载中心</span> </h2>
                    <p><a href="">安卓数据采集软件</a></p>
                </li>
                <li class="content">
                    <p class="number">400-766-9696</p>
                    <p>周一至周五 9:00-18:00</p>
                    <p class="mgt10">
                        <a href="" class="kfbg">8小时在线客服</a>
                    </p>
                </li>
            </ul>
        </div>
    </div>
</div>
</template>

<script>

export default {
  name: 'HomeAbout',

}
</script>

<style lang="stylus" scoped>
.bottom
    width 1366px
    padding: 30px 0;
    border: 1px solid #d3d5d7
    border-left 0
    border-right 0
    margin 0 auto 
    background #ebebeb
    .innerCon
        width 1255px
        margin 0 auto 
        .clearfix
            
            clear : ''
            display inline-block
            li
                float left
                text-align center
                border-right 1px solid #ccc
                width 312px
                h2
                    margin-bottom 3px
                    span
                        display inline-block
                        width 120px
                        height 34px
                        line-height 34px
                        font-size  16px
                        font-weight normal
                        color #000
                        background-color #ccc 
                        border-radius 17px
                p
                    line-height 24px
                    font-size 5px
                    a
                        color #383839
            .content
                border  0
                color #000
                .number
                    font-size 24px
                    color #ff4a00
                    font-weight bolder
                    margin-bottom 4px
                .mgt10
                    margin-top 10px
                    .kfbg
                        display inline-block
                        border-radius 17px
                        width 140px
                        height 34px
                        line-height 34px
                        vertical-align center
                        color #ffffff
                        font-weight bolder
                        background-color #ff4a00


</style>
