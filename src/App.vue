<template>
  <div id="app">
    <home></home>
  </div>
</template>

<script>
import home from './components/home.vue'


export default {
  name: 'app',
  data (){
    return{
    }
  },
  components:{home}
}
</script>

<style>
*{
  padding:0;
  margin:0;
}
body,html{
  width: 100%;
  height: 100%;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
  height: 100%;
}
</style>
