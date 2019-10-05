<template>
  <div id="room">
      <h2>班级座位表</h2>
      <Seat  name="姓名1" v-bind:score="12" seatLeft="0px" seatTop="0px"></Seat>
      <Seat  name="姓名2" v-bind:score="12" seatLeft="160px" seatTop="0px"></Seat>
      <Seat  name="姓名3" v-bind:score="12" seatLeft="320px" seatTop="0px"></Seat>
      <Seat  name="姓名4" v-bind:score="12" seatLeft="480px" seatTop="0px"></Seat>
      <Seat  name="姓名5" v-bind:score="12" seatLeft="640px" seatTop="0px"></Seat>
      <Seat  name="姓名6" v-bind:score="12" seatLeft="800px" seatTop="0px"></Seat>
      <Seat  name="姓名7" v-bind:score="12" seatLeft="0px" seatTop="160px"></Seat>
      <Seat  name="姓名8" v-bind:score="12" seatLeft="160px" seatTop="160px"></Seat>
      <Seat  name="姓名9" v-bind:score="12" seatLeft="320px" seatTop="160px"></Seat>
      <Seat  name="姓名10" v-bind:score="12" seatLeft="480px" seatTop="160px"></Seat>
      <Seat  name="姓名11" v-bind:score="12" seatLeft="640px" seatTop="160px"></Seat>
      <Seat  name="姓名25" v-bind:score="12" seatLeft="640px" seatTop="640px"></Seat>
      <Seat  name="姓名36" v-bind:score="12" seatLeft="800px" seatTop="800px"></Seat>
  </div>
  
</template>
  

<script>
import Seat from './Seat.vue'

export default {
  name: 'Seats',
  props: {
    name:String,
    score:Number,
  },
  components: {
    Seat,
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div#room{
    width: 1000px;
    height: 1000px;
    border:1px dashed red;

    position: relative;
    /* top: 50px;
    left: 100px; */
    margin: 0 auto;
}


</style>
