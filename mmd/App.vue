<template>
  <div id="app">
    <div id="nav">
      <div class="logo"></div>
    </div>
      <div class="ic"></div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#nav{
  width: 100%;
  height: 70px;
  background-color:rgb(255, 68, 102);
}
.logo{
    background: url(https://www.hanfugou.com/Image/base_icon.png?v=3);
    width: 310px;
    height: 36px;
    display: inline-block;
    margin-top: 18px;
}
.ic{
      width: 14px;
    height: 14px;
    background: url(https://www.hanfugou.com/Image/base_icon.png?v=3) no-repeat 0 -230px;
    display: inline-block;
    vertical-align: middle;
    margin: -2px 4px 0 0;
}
</style>
