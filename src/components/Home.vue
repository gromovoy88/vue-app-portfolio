<template>
  <div class="home">
    <header-page/>
  </div>
</template>

<script>
import Vue from 'vue'
import Header from './Header'

Vue.component('header-page', Header)

export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
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
  .home {
    height: 90vh;
    .container {
      height: 100%;
    }
  }
</style>
