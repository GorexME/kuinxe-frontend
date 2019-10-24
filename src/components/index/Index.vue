<template>
  <div class="main">
      <h1>{{ msg }}</h1>
      <p>
          Whelcome to Kuinxe
      </p>
  </div>
</template>

<script>
export default {
    name: 'Index',
    props: {
        msg: String
    }
}
</script>

<style lang="scss">
h1 {
    margin: 40px 0 0;
    color: #42b983;
}
</style>