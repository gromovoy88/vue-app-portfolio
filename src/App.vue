<template>
  <div id="app">
    <div class="container-fluid" id="mainContainer">
      <nav class="navbar sticky-top navbar-light">
        <span class="navbar-brand mb-0 h1">hromovyi.</span>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      </nav>
      <router-view/>
    </div>
  </div>
</template>
<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
  @import "~bootstrap/scss/bootstrap";
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
  #mainContainer {
    padding-left: 0;
    padding-right: 0;
  }
  .navbar{
    background-color: transparent;
  }
</style>
