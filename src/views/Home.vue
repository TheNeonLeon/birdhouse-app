<template>
  <div class="home">
    <img alt="birdhouse-logo" src="../assets/birdhouse.png">
    <Welcome msg="Welcome to Birdhouse"/>
  </div>
</template>

<script>
// @ is an alias to /src
import '@/styles/base.sass'

export default {
  name: 'Home'
}
</script>

<style lang="scss">
@import '../styles/base.sass';

body {
  background-color: $primary-background-colour
}
</style>
