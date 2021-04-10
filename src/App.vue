<template>
  <div class="docker">
    <div class="docker__item">
      <span class="iconfont" style="display: inline-block">&#xe60b;</span>
      首页
    </div>
    <div class="docker__item">购物车</div>
    <div class="docker__item">订单</div>
    <div class="docker__item">我的</div>
  </div>
</template>

<style lang="scss">
.docker {
  position: absolute;
  left: 0;
  height: 0.49rem;
  padding: 0 0.18rem;
  box-sizing: border-box;
  bottom: 0;
  display: flex;
  width: 100%;
  border-top: 1px solid #f1f1f1;
}
.docker__item {
  flex: 1;
  text-align: center;
}
</style>
