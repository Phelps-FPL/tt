<template>
<div>
      <home-header></home-header>
      <home-nav></home-nav>
      <home-product></home-product>
</div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeNav from './components/Nav'
import HomeProduct from './components/Product'
export default {
  name: 'Home',
  components:{
    HomeHeader,
    HomeNav,
    HomeProduct
  }
}
</script>

<style lang="stylus" scoped>

</style>
