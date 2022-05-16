<template>
  <div>
    <h2>about</h2>
    <h3>{{this.$route.params.id}}</h3>
  </div>
</template>

<script>
export default {
  name: 'about',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
