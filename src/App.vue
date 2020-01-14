<template>
  <div id="app">
    <app-nav />
    <router-view class="container" />
  </div>
</template>

<script>
  /* eslint-disable import/extensions */

  import AppNav from './components/AppNav'

  export default {
    components: {
      AppNav
    }
  }
</script>

<style lang="scss">
</style>
