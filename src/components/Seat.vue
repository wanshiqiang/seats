<template>
  <div>
      <!-- <img alt="Vue logo" src="../assets/logo.png">
      <b>{{name}}</b>
      <b>{{score}}</b>
      <Button type="primary">Primary</Button>
      <Button type="dashed">Dashed</Button>
      <Button type="text">Text</Button>
      <Button type="info">Info</Button>
      <Button type="success">Success</Button>
      <Button type="warning">Warning</Button>
      <Button type="error">Error</Button> -->
      <br><br>
      <Card style="width:200px">
        <p slot="title">
            <Icon type="ios-school"></Icon>
            学生1
        </p>

        <Avatar icon="ios-person" size="large" />
        <span>得分：67</span>
        <!-- <span>
            总分：234
        </span> -->
    </Card>
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
