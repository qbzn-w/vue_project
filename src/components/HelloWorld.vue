<template>
  <div>
    <button v-on:click="goabout()">Add 1</button>
    <button v-on:click="goparam()">goparam</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods: {
    goabout: function () {
      this.$router.push('/about')
    },
    goparam: function () {
      this.$router.push({name: 'about', params: {id: '1000'}})
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
