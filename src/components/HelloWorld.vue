<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>{{header}}</h3>
    <p>Enter in your hobby</p>
    <input type="text">

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Third Vue App',
      header: 'Get started',
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
