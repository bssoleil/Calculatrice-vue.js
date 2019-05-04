<template>
  <div id="app">
    <Calculatrice/>
  </div>
</template>

<script>
import Calculatrice from './components/Calculatrice.vue'

export default {
  name: 'app',
  components: {
    Calculatrice,
  }
}
</script>

<style lang="scss">
#app {
font-family: 'Avenir', Helvetica, Arial, sans-serif;
text-align: center;
margin-top: 90px;
}
</style>

