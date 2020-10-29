<template>
  <div class="home">
    <img alt="birdhouse-logo" src="../assets/birdhouse.png">
    <Welcome msg="Welcome to Birdhouse"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Welcome from '@/components/Welcome.vue'

export default {
  name: 'Home',
  components: {
    Welcome
  }
}
</script>

<style>
body{
  background: #4FF77E;
}
</style>
