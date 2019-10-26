<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/Cogwheels.png">
    <Home msg="Under contruction"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Home from '@/components/Home.vue'

export default {
  name: 'home',
  components: {
    Home
  }
}
</script>

<style>
img {
  width: 35%;
}
</style>
