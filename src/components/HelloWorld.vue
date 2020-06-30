<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2 class="hello2">Essential Links</h2>
    <h2>Ecosystem</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
    .hello {
      background: red;
        .hello2 {
          color: blue;
        }
    }
</style>
