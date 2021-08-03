<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li>Some rendom text</li>
      <li>Some rendom text</li>
      <li>Some rendom text</li>
      <li>Some rendom text</li>
    </ul>
    <hr>
    <button class="btn">Test button for SCSS</button>
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
<style lang="scss">
ul {
  background: $kkk;
}
</style>
