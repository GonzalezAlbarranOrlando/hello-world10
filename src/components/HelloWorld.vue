<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>{{helloWorld}}</h2>
    <hr/>
    <div style="background: gray">
      <MyTest/>
    </div>
  </div>
</template>

<script>
import MyTest from './MyTest.vue'

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data(){
    return{
      helloWorld: 'Hello World!'
    }
  },
  components: {
    MyTest
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
