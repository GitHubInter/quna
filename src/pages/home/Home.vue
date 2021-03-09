<template>
  <div class="hello">
    <home-header></home-header>
    <home-swiper></home-swiper>
  </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwiper from './components/Swiper'
export default {
  name: 'HelloWorld',
  components: {
    HomeHeader,
    HomeSwiper
  },
  data () {
    return {
      msg: 'HelloWorld'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
