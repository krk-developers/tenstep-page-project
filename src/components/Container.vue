<template>
  <div class="container">
    <app-header></app-header>
    <app-main></app-main>
    <app-footer></app-footer>
  </div>
</template>

<script>
import AppHeader from './Container/App-header.vue';
import AppMain from './Container/App-main.vue';
import AppFooter from './Container/App-footer.vue';

export default {
  components: {
    'app-header': AppHeader,
    'app-main': AppMain,
    'app-footer': AppFooter
  }
}
</script>

<style lang="scss">
  .container{
    max-width: 1366px;
    min-height: 800px;
    background: #fff;
    margin: 0 auto;
  }
</style>
