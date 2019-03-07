<template>
  <div id="app">
    <Container></Container>
  </div>
</template>

<script>
import Container from './components/Container.vue'

export default {
  name: 'app',
  components: {
    Container
  }
}
</script>

<style lang="scss">
body{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background: hsl(200, 100%, 80%);
}
</style>
