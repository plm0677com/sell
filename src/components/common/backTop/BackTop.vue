<template>
  <div class="back-top">
    <img src="~assets/img/common/top.png" alt="">
  </div>
</template>

<script>
export default {
  name: "BackTop"
}
</script>

<style scoped>
  .back-top{
    position: fixed;
    bottom: 50px;
    right: 10px;
    z-index: 10;
  }
  .back-top img{
    width: 43px;
    height: 43px;
  }
</style>
