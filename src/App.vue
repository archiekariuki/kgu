<template>
  <div id="app">
    <h1>{{msg}}</h1>
    <navbar />
    
  </div>
</template>

<script>
import navbar from './navbar'
export default {
  name: 'app',
  components:{
    navbar
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>

</style>
