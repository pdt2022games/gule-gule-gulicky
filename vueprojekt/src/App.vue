<template>
  <PrvaGula msg="Welcome to Your Vue.js App"/>
</template>

<script>
import PrvaGula from './components/PrvaGula.vue'

export default {
  name: 'App',
  components: {
    PrvaGula
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  font-weight: bolder;
  font-size: 20px;
  color: black;
  margin-top: 60px;
  align-items: center;
  justify-content: center;
}
</style>
