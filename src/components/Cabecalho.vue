<template>
  <div class="cabecalho">
    <img class="brand" alt="Vue logo" src="../assets/logo.png">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Cabecalho',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.cabecalho{
  height: 250px;
}
.cabecalho h1{
  display:inline-block;
  position: absolute;
  right: 300px;
}
.brand{
  display:inline-block;
  position: absolute;
  left:300px;
}
.clear{
  clear: both;
  }
</style>
