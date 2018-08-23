<template>
  <div id="app">
    <img src="./assets/logo.png">
    <CrackOn msg="Get cracking!"/>
  </div>
</template>

<script>
  import CrackOn from './components/CrackOn.vue'

  export default {
    name: 'app',
    components: {
      CrackOn
    }
  }
</script>

<style lang="scss" scoped>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    margin-top: 60px;

    img {
      max-width: 200px;
      margin: 0 auto;
    }
  }
</style>
