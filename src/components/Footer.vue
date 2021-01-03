<template>
  <div class="footer">
    <p>Copyright Fuji Inc. 保留所有权利。 隐私政策 使用条款 销售政策 法律信息 网站地图</p>
  </div>
</template>

<script>
export default {
name: "Footer"
}
</script>

<style scoped>
.footer {
  position: fixed;
  bottom: 0;
  margin-left: -800px;
  padding: 0;
  height: 50px;
  width: 1600px;
  left: 50%;
  z-index: 99;
  text-align: center;
}
</style>