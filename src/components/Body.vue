<template>
  <div class="body">
    <div class="content">
      <img class="img-logo" src="../img/fuji1230.png"/>
      <div class="production" v-show="true">
        <div class="production-info">
          <h1>Talking</h1>
        </div>
        <div class="production-info">
          <h1>Lion VIP</h1>
        </div>
        <div class="production-info">
          <h1>FUJI TUBE</h1>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Body",
  data: function () {
  }
}
</script>

<style scoped>
.body {
  height: 100%;
  width: 100%;
  overflow: hidden;
}

.content {
  height: 100%;
  width: 100%;
}

.img-logo {
  height: 100%;
  width: 100%;
  position: absolute;
}

.production {
  margin-top: 10%;
  left: 5%;
  right: 5%;
  width: 90%;
  height: 60%;
  position: absolute;
}

.production-info {
  left: 2%;
  right: 2%;
  width: 32%;
  height: 100%;
  float: left;
  margin-left: 1%;
  background-color: green;
}
</style>
