<template>
  <div>
    <div class="product">
      <div class="innerPro">
          <div class="hotProduct">
              <h2><span class="el-icon-search"></span> 热门产品</h2>
        <el-carousel indicator-position="outside" style="overflow:hidden">
          <el-carousel-item >
                    <ul class="ulList">
                      <li  style="width:313px;float:left; display: block;" v-for="(item,id) in imgs" :key="id">
                        <a href=""><img :src="item.url" alt="">
                        </a>
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
  data () {
      return {
          
              imgs:[{id:'0001',url:'../../../static/product/D7.png'},
                {id:'0002',url:'../../../static/product/E7.png'},
                {id:'0003',url:'../../../static/product/P6.png'},
                {id:'0004',url:'../../../static/product/P7.png'},
                ]
        
      }
  }
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


