<template>
  <div class="stu" v-bind:style = {top:seatTop,left:seatLeft}>
      <Card>
      <!-- <Card class="stu"> -->
        <p slot="title">
            <Icon type="ios-school"></Icon>
            {{name}}
        </p>
        <Avatar icon="ios-person" size="large" />
        <span id="score">得分：{{score}}</span>
        {{seatTop}}{{seatLeft}}
    </Card>
  </div>
</template>
  

<script>
export default {
  name: 'Seat',
  
  props: {
    name:String,
    score:Number,
    seatTop: String,
    seatLeft: String,
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  span#score {
    margin: 5px;
  }
  .stu{
    width:150px;

    position:absolute;
  }
</style>
