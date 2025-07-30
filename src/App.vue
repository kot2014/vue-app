<template>
  <DefaultLayout>
    <HomeView />
  </DefaultLayout>
</template>

<script>
import DefaultLayout from './layouts/DefaultLayout.vue'
import HomeView from './views/HomeView.vue'

export default {
  name: 'App',
  components: {
    DefaultLayout,
    HomeView
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
body {
  margin: 0;
}
</style>
