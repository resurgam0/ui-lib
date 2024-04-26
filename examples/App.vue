<template>
  <div id="app">
    <m-card imgSrc="demo.jpg" summary="简直很多哈哈哈喀什哈哈哈"></m-card>
    <br>
    <m-card imgSrc="demo2.jpg" summary="简直33哈喀什哈哈哈">
      <template v-slot:footer>
        <div class="footer">
          <div class="level">中级黄金价</div>
          <div class="price">￥12.00</div>
        </div>
      </template>
    </m-card>
    <br>
    <m-card imgSrc="demo3.jpg" :width="370" :imgHeight="90">
      本路线旨在帮助想快速掌握应用的工程师，全方位多角度得带你升级
      <template v-slot:footer>
        <div class="footer-spring">
          <div class="level">4步骤</div>
          <div class="level">4步骤</div>
        </div>
      </template>
    </m-card>
  </div>
</template>

<script>


export default {
  name: 'App',

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.footer{
  padding: 0 8px;
  font-size: 12px;
  text-align: left;
}
.level{
  color: #9199A1;
  margin-bottom: 8px;
}
.price{
  color: #F01414;
}
.footer-spring{
  display: flex;
  justify-content: space-between;
  padding: 0 8px;
  font-size: 12px;
}
</style>
