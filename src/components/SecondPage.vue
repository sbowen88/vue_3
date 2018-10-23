<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>{{header}}</h3>
<input v-model="first_message" placeholder="edit me">
<p class = 'first_message'>Message is: {{ first_message }}</p>
<span>Multiline message is:</span>
<p style="white-space: pre-line;">{{ message }}</p>
<br>
<textarea v-model="message" placeholder="add multiple lines"></textarea>

  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Third Vue App",
      header: "Second Page",
      first_message: "",
      message: ""
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
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
.first_message{
  color: red;
}
</style>
