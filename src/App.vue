<template>
  <div id="app">
    <AppNavBar/>
    <router-view/>
    <AppFooter/>
  </div>
</template>

<script>
import AppNavBar from '@/components/AppComponents/AppNavBar'
import AppFooter from '@/components/AppComponents/AppFooter'

export default {
  name: 'App',
  components:{
    AppNavBar,
    AppFooter
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
