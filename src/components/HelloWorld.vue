<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Application to test issue with vue-devtools when one of component has Proxy in data or properties.
    </p>
    <p><a href="https://github.com/vuejs/vue-devtools/issues/708" target="_blank">issue page</a></p>
    <p><a href="https://github.com/vuejs/vue-devtools/pull/709" target="_blank">Pull request</a></p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    proxy: Function
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
