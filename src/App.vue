<template>
  <div id="app">
    <myheader></myheader>
    <mycontent message='hello hello'></mycontent>
  </div>
</template>

<script>
/** 子コンポーネントの読み込み */
import myheader from './components/myheader'
import mycontent from './components/mycontent'

/** 子コンポーネントを使うことをここで宣言 */
export default {
  name: 'App',
  components: {
    myheader,
    mycontent
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
