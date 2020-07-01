<template>
  <div class="main">
    <h1>Will Lewis Williams</h1>
    <h2>Student programmer</h2>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h1, h2 {
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
  color: #2c3e50;
}

h1 {
  margin-top: 40px;
}
</style>