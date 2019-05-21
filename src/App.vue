<template>
  <div id="app">
  <router-link to="/view1">Go to view1</router-link>
<router-link to="/view2">Go to view2</router-link>
<!-- 路由出口 -->
<!-- 路由匹配到的组件将渲染在这里 -->
<router-view></router-view>
    <img src="./assets/logo.png">
    <router-view/>
      <firstcomponent></firstcomponent>
  </div>
</template>
<import firstcomponent from './components/first-component.vue'>

<script>
export default {
  name: 'App',
  　　data () {
　　　　return {
　　　　　　msg: 'Welcome to Your Vue.js App'
　　　　}
　　}
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
