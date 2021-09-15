<template>
  <div id="app">
    <header-component />
    <router-view/>
    <footer-component />
  </div>
</template>

<script>
import HeaderComponent from '../src/components/header/Header'
import FooterComponent from '../src/components/footer/Footer'

export default {
  name: 'App',
  props: [],
  data () {
    return {}
  },
  computed: {},
  created () {},
  mounted () {},
  watch: {},
  methods: {},
  components: { HeaderComponent, FooterComponent}
}
</script>

<style lang="scss">
  @import "assets/style/common.scss";
</style>
