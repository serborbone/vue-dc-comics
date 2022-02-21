<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <HeaderDc></HeaderDc>
    <MainDc></MainDc>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MainDc from './components/MainDc.vue'
import HeaderDc from './components/HeaderDc.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    HeaderDc,
    MainDc,
  }
}
</script>

<style lang="scss">
  
  @import "assets/general.scss";

</style>
