<template>
  <div id="app">
    <myheader></myheader>
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
/** 子コンポーネントの読み込み */
import myheader from './components/myheader'

/** 子コンポーネントを使うことをここで宣言 */
export default {
  name: 'App',
  components: {
    myheader
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
