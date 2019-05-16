<template>
<div>
      <home-header></home-header>
      <home-nav></home-nav>
      <home-product></home-product>
      <home-about></home-about>
      <home-footer></home-footer>
</div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeNav from './components/Nav'
import HomeProduct from './components/Product'
import HomeAbout from './components/About'
import HomeFooter from './components/Footer'
export default {
  name: 'Home',
  components:{
    HomeHeader,
    HomeNav,
    HomeProduct,
    HomeAbout,
    HomeFooter
  }
}
</script>

<style lang="stylus" scoped>

</style>
