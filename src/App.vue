<template>
  <BlockCountdown/>
</template>

<script>
import BlockCountdown from './components/BlockCountdown.vue'

export default {
  name: 'App',
  components: {
    BlockCountdown
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
