<template>
  <div>
    <div class="product">
      <div class="innerPro">
          <div class="hotProduct">
              <h2><span class="el-icon-search"></span> 热门产品</h2>
        <el-carousel :autoplay='false' indicator-position="outside" style="overflow:hidden">
          <el-carousel-item v-for="item in List" :key="item" >                   
                    <ul class="List"> 
                        <li  style="width:313px;float:left; display: block;" v-for="i in item.imgs" :key="i">
                          <div class="Pic">
                        <a href=""><img :src="i.url" alt=""> </a>
                        <h3><a href="" >{{i.num}}</a></h3>
                        <p class="text">
                          <i class="inner">{{i.text}}</i>
                          </p>                      
                         </div>
                        </li>
                      </ul>
                                        
          </el-carousel-item>
        </el-carousel>
            </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeProduct",
 data() {
   return {
     List:[{
       id:'0001',
       imgs:[{url:'../../../static/product/D7.png',num:'D7',text:'全屏触控，感受指尖的律动，更清晰更全面'},
             {url:'../../../static/product/E7.png',num:'E7',text:'大屏显示,放松你的双眼,更宽的视觉效果,更好的视觉体验'},
             {url:'../../../static/product/P6.png',num:'P6',text:'越夜越精彩，星光夜视智能后视镜'},
             {url:'../../../static/product/P7.png',num:'P7',text:'星光夜视智能后视镜，星光璀璨，一见倾心'}]
        },
       {
        id:'0002',
        imgs:[{url:'../../../static/product/D7.png',num:'D8',text:'全屏触控，感受指尖的律动，更清晰更全面'},
              {url:'../../../static/product/E7.png',num:'E7',text:'大屏显示,放松你的双眼,更宽的视觉效果,更好的视觉体验'},
              {url:'../../../static/product/P6.png',num:'P6',text:'越夜越精彩，星光夜视智能后视镜'},
              {url:'../../../static/product/P7.png',num:'P7',text:'星光夜视智能后视镜，星光璀璨，一见倾心'}
        ]
       },
        {
        id:'0003',
        imgs:[{url:'../../../static/product/D7.png',num:'D7',text:'全屏触控，感受指尖的律动，更清晰更全面'},
              {url:'../../../static/product/E7.png',num:'E7',text:'大屏显示,放松你的双眼,更宽的视觉效果,更好的视觉体验'},
             {url:'../../../static/product/P6.png',num:'P6',text:'越夜越精彩，星光夜视智能后视镜'},
             {url:'../../../static/product/P7.png',num:'P7',text:'星光夜视智能后视镜，星光璀璨，一见倾心'}
             ]
       },
     ]
   }
 },
};

</script>
<style lang="stylus" scoped>
.product
    width 1500px
    margin-top 10px
    margin 0 auto
    .innerPro
        width 1255px
        margin 0 auto
        .hotProduct
            position relative
            margin 18px 0 28px 0
            box-shadow 0 1px 4px rgba(0,0,0,.2)
            h2
                margin-bottom 6px
                .el-icon-search
                  display inline-block
                  width 26px
                  height 26px
                  vertical-align center
                  margin-right 3px
            .Pic
              text-align center
              h3
                margin-top 3px
              .text
                color #666
                height 16px
                .inner
                  width 16em
                  display inline-block


</style>


