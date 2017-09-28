<template>
  <div id="app">
    {{ $store.state.count }}
    <counter></counter>
    <counter></counter>
    <reset></reset>
    <async-counter></async-counter>
  </div>
</template>

<script>
import Counter from './components/Counter'
import Reset from './components/Reset'
import AsyncCounter from './components/AsyncCounter'
export default {
  name: 'app',
  components: {
    Counter,
    Reset,
    AsyncCounter
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
