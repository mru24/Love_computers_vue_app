<template>
  <div>
    <navbar></navbar>
    <router-view></router-view>
  </div>
</template>

<script>
import navbar from './components/navbar.vue'

export default {
  components: {
    navbar
  }
}
</script>

<style lang="sass">

@import './components/config'

</style>
