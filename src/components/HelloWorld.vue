<template>
  <div class="hello">
    {{5+5}}<br>
    {{ ok ? 'YES' : 'NO' }}<br>
    {{ message.split('').reverse().join('') }}
    <div v-bind:id="'list-' + id">菜鸟教程</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      ok: true,
      message: 'RUNOOB',
      id : 1
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
.class1{
  background: #444;
  color: #eee;
}
</style>
