<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <PrimerComponente/>
</template>

<script>
import PrimerComponente from './components/Counter.vue'

export default {
  name: 'Componente',
  components: {
    PrimerComponente
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