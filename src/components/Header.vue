<template>
  <div class="section-about">
    <div class="container">
      <div class="row align-items-center header">
        <div class="col-6">
          <h1>Hi!</h1>
          <h1>I`m</h1>
          <h1>Designer</h1>
        </div>
        <div class="col-6">
          <div class="collapse" id="navbarToggleExternalContent">
            <div class="bg-dark p-4">
              <h5 class="text-white h4">Collapsed content</h5>
              <span class="text-muted">Toggleable via the navbar brand.</span>
            </div>
          </div>
        </div>
      </div>
      <div class="row contacts">
        <div class="col-12">
          <font-awesome-icon :icon="['fab', 'facebook-f']" />
          <font-awesome-icon :icon="['fab', 'instagram']" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
  .section-about {
    height: 100%;
  }
  .header {
    height: 90%;
  }
  .contacts {
    height: 10%;
  }
</style>
