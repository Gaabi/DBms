<template>
  <div id="app">
   <img src ="./assets/pesit_logo.png" align=left  > 
   <userend> </userend>
    <router-view></router-view>
  </div>
</template>

<script>
import userend from './components/userend'
export default {
  name: 'app',
  components :{
    userend
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
  background-color:#33C1FF  ;

}
</style>
