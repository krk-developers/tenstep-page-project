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
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  background: hsl(200, 100%, 80%);
  font-family: 'Arial';
  font-size: 16px;
}
</style>
