<template>
  <div>
    <div style="float: left;">
      <img src="../../img/profile_pic.jpg" />
    </div>
    <div style="float: right;">
      Hello
    </div>
  </div>
</template>

<script>
export default {
  name: 'Main',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.img {
    position: absolute;
    height: 100%;
    top: 0;
    bottom: 0;
}
</style>
