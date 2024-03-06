<template>
  <div id="app">
    <HeaderComponent v-if="$route.name !== 'login'" />
    <template v-if="$route.name !== 'login'">
      <router-view />
    </template>
    <template v-else>
      <router-view />
    </template>
    <FooterLayout v-if="$route.name !== 'login'" />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import FooterLayout from '../src/components/FooterComponent.vue'

export default {
  components: {
    HeaderComponent,
    FooterLayout
  }
}
</script>
<style lang="scss">
@import './assets/styles/custom';
@import '../node_modules/bootstrap/scss/bootstrap';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
