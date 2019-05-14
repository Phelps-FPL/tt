<template>
  <div>
    <div class="indexSlider">
      <div class="floatleft categorys">
        <ul>
          <li>
            <div class="productList">
              <h2>电子狗</h2>
              <a href="#">云电子狗</a>
            </div>
          </li>
          <li>
            <div class="productList">
              <h2>行车记录仪</h2>
              <a href>T06</a>
              <strong>|</strong>
              <a href>D35</a>
              <strong>|</strong>
              <a href>S5</a>
            </div>
          </li>
          <li>
            <div class="productList">
              <h2>行车记录仪</h2>
              <a href>T06</a>
              <strong>|</strong>
              <a href>D35</a>
              <strong>|</strong>
              <a href>S5</a>
              <strong>|</strong>
              <a href>S5</a>
              <strong>|</strong>
              <a href>S5</a>
              <strong>|</strong>
              <a href>S5</a>
              <strong>|</strong>
              <a href>S5</a>
              <strong>|</strong>
              <a href>S5</a>
              <strong>|</strong>
              <a href>S5</a>
              <strong>|</strong>
              <a href>S5</a>
            </div>
          </li>
          <li>
            <div class="productList">
              <h2>云伴侣</h2>
              <a href>云伴侣</a>
            </div>
          </li>
        </ul>
      </div>
      <div class="floatleft">
        <div class="outFlexPic ">
            <el-carousel style="height: 422px" trigger="click" >
            <el-carousel-item  v-for="item in imgs" :key="item">
                <div ><img :src="item.url" alt=""></div>
            </el-carousel-item>
            </el-carousel>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeContent",
  data() {
      return {
          imgs:[
              {id:'0001',url:'../../static/swiper/1.jpg'},
              {id:'0002',url:'../../static/swiper/2.jpg'},
              {id:'0003',url:'../../static/swiper/1557842303781.jpg'},
              {id:'0004',url:'../../static/swiper/4.jpg'},
          ]
      }
  },
};
</script>

<style lang="stylus" scoped>
.outFlexPic >>> .el-carousel__container
    height 422px 
.indexSlider 
    width: 1500px;
    margin: 0 auto;
    position: relative;
    display: block;
    border-bottom: 1px solid #d3d5d7;
    border-left: 1px solid #d3d5d5;
    height: 422px;
        
  .outFlexPic
      width 1177px
      height 422px
      position relative
       .el-carousel__item h3 {
        color: #475669;
        font-size: 14px;
        opacity: 0.75;
        line-height: 150px;
        margin: 0;
            }

        .el-carousel__item:nth-child(2n) {
            background-color: #99a9bf;
        }
  
        .el-carousel__item:nth-child(2n+1) {
            background-color: #d3dce6;
        }
      img
        height 422px
        width 100%
  .floatleft 
      float: left;
  

  .categorys
    border-right: 1px solid #d3d3d3;
    width: 321px;
    background: #ffffff;
    z-index: 10;
    height: 422px;
  
    li
      padding: 15px 25px 15px 45px;
      border-bottom: 1px solid #d3d5d5;
      line-height: 20px;

      h2 
        color: #ff4a00;
        font-size: 14px;
        margin-bottom: 4px;
      

      a
        color: #404144;
        display: inline-block;
        cursor: pointer;
      


</style>
