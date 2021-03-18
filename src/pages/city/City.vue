<template>
  <div>
    <city-header></city-header>
    <city-search :cities="cities"></city-search>
  </div>
</template>

<script>
import CityHeader from './components/Header'
import CitySearch from './components/Search'
export default {
  name: 'City',
  components: {
    CityHeader,
    CitySearch
  },
  data () {
    return {
      cities: {}
    }
  }
}
</script>

<style>

</style>
