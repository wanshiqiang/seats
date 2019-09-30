<template>
  <div>
      <img alt="Vue logo" src="../assets/logo.png">
      <b>{{name}}</b>
      <b>{{score}}</b>
  </div>
</template>

<script>
export default {
  name: 'Seat',
  props: {
    name:String,
    score:Number,
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
