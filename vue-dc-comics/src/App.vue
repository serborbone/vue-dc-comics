<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <HeaderDc></HeaderDc>
    <MainDc></MainDc>
    <FooterDc></FooterDc>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MainDc from './components/MainDc.vue'
import HeaderDc from './components/HeaderDc.vue'
import FooterDc from './components/FooterDc.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    HeaderDc,
    MainDc,
    FooterDc,
  }
}
</script>

<style lang="scss">
  
  @import "assets/general.scss";

</style>
