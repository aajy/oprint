<template>
  <HeaderComponent/>
  <HomeComponent msg="homePage"/>
</template>

<script>
import HomeComponent from './components/HomeComponent.vue'
import HeaderComponent from './components/common/HeaderComponent'

export default {
  name: 'App',
  components: {
    HomeComponent,
    HeaderComponent
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
}
</style>
