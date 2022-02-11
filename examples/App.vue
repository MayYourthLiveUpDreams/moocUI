<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Demo />
    <m-card 
      imgSrc="11551db45ab0c652796b24c15dd68f9a.jpeg" 
      summary="计算机课学与技术" 
    />
    <m-card imgSrc="45b848e3eba3d3733f544003bf5d3e80.jpeg" summary="计算机科学与技术">
      <template v-slot:footer>
        <div class="footer">
          <div class="level">中级518人报名</div>
          <div class="price">￥299.0</div>
        </div>
      </template>
    </m-card>
    <m-card imgSrc="517477beeedeb285a717de27a0386d01.jpeg" summary="西北师范大学" :width="370" :imgHeight="90">这是对高度的测试
      <template v-slot:footer>
        <div class="footer-spring">
          <div class="level">
            4步骤 - 6门课
          </div>
          <div class="price">10965收藏</div>
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
  color: #000;
}
.footer-spring{
  color: #342f78;
}
</style>
