<template>
  <div class="nav-bar">
    <div class="left"><slot name="left"></slot></div>
    <div class="center"><slot name="center"></slot></div>
    <div class="right"><slot name="right"></slot></div>
  </div>
</template>

<script>

</script>

<style>
.nav-bar{
  width: 100%;
  position: fixed;
  top:0;
  left: 0;
  height: 45px;
  line-height: 45px;
  display: flex;
}
.left{
  width: 20%;
  background: red;
}
.center{
  width: 60%;
  background: yellow;
  text-align: center;
}
.right{
  width: 20%;
  background: red;
}
</style>