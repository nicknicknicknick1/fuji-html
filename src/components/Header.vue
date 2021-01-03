<template>
  <div class="header">
    <img class="logo" src="../img/fujilogo.png" />
    <p id="menu-1" v-on:click="counter += 1">产品</p>
    <P>我们</P>
    <P class="more">...</P>
  </div>
</template>

<script>
export default {
  name: 'Header',
  el: '#menu-1',
  data: function() {
    return {
      counter: 0
    };
  },
  methods: {

  }
}
</script>

<style scoped>
.header {
  position: fixed;
  top: 0;
  margin-left: -25%;
  padding: 0;
  height: 80px;
  width: 65%;
  left: 45%;
  z-index: 99;
  background-color: #1da1f2;
}

.logo {
  height: 50px;
  width: 100px;
  margin: 15px 10px 5px 10px;
  float: left;
}

p {
  margin: 32px 10px 15px 30px;
  font-size: 16px;
  color: #fff;
  line-height: 1.07143;
  float: left;
}

.more {
  margin: 10px 20px 20px 30px;
  font-size: 36px;
  color: #fff;
  line-height: 1.07143;
  float: left;
}
</style>