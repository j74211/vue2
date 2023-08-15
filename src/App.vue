<template>
  <div id="app">
    <img alt="Vue logo" class="iogo" src="https://img2.baidu.com/it/u=267632856,3740526320&fm=253&fmt=auto&app=120&f=JPEG?w=1280&h=800">
    <HelloWorld msg="新时代没有能够承载我的船，艾斯！！！再一次修改"/>
  </div>
</template>
<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
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
</style>
