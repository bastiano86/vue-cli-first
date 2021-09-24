<template>
  <div id="app">
    <jumbotron/>
    <primaScritta/>
  </div>
</template>

<script>
import primaScritta from '@/components/primaScritta.vue'
import jumbotron from '@/components/jumbotron.vue'

export default {
  name: 'App',
  components: {
    primaScritta,
    jumbotron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
