<template>
  <div id="app">
    <HeaderComponent v-if="$route.name !== 'login'"  />
    <router-view v-if="$route.name !== 'login'" />
    <router-view v-else />
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

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
