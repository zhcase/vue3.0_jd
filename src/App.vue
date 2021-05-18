<!--
 * @Author: zeHua
 * @Date: 2021-05-18 17:40:45
 * @LastEditors: zeHua
 * @LastEditTime: 2021-05-18 19:57:36
 * @FilePath: /imooc/vue3.0_jd/src/App.vue
-->
<template>
  <div>
    <div class="wrapper">
      <div class="position">
        <span class="iconfont position-icon"></span>
        北京理工大学北校区103室
      </div>
    </div>
    <div class="docker">
      <div class="docker__item docker__item--active">
        <span class="iconfont icon-home" style="display: inline-block"></span>
        <div class="docker__title">首页</div>
      </div>
      <div class="docker__item">
        <span
          class="iconfont icon-shop-cart-1"
          style="display: inline-block"
        ></span>
        <div class="docker__title">购物车</div>
      </div>
      <div class="docker__item">
        <span class="iconfont icon-order" style="display: inline-block"></span>
        <div class="docker__title">订单</div>
      </div>
      <div class="docker__item">
        <span class="iconfont icon-center" style="display: inline-block"></span>
        <div class="docker__title">我的</div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.wrapper {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0.5rem;
  padding: 0 0.18rem;
}
.position {
  padding: 0.16rem 0;
  line-height: 0.22rem;
  font-size: 0.16rem;
  &__icon {
  }
}
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
  &__item {
    flex: 1;
    text-align: center;
    .iconfont {
      margin: 0.07rem 0 0.02rem 0;
      font-size: 0.18rem;
    }
  }
  &__title {
    transform: scale(0.5, 0.5);
    font-size: 0.2rem;
    transform-origin: center top;
  }
}

.docker__item--active {
  color: #1fa4fc;
}
</style>
