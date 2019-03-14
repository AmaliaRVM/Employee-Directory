<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Homepage/>
    <EmployeePage/>

  </div>
</template>

<script>
/* import HelloWorld from './components/HelloWorld.vue' */
import Homepage from './components/Homepage.vue'
import EmployeePage from './components/EmployeePage.vue'

export default {
  /* name: 'app', */
  components: {
    /* HelloWorld */
    Homepage,
    EmployeePage,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  display: flex;
  justify-content: space-around;
  color: #2c3e50;
  border: solid black;
  width: 95vw;
  height: 95vh;
}
</style>
