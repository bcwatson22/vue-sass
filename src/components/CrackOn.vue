<template>
  <div class="wrapper">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style lang="scss" scoped>
  @import './../assets/styles/sass/_variables.scss';

  h1 {
    color: $purple;
  }
</style>
