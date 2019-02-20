<template>
  <div id="app">
    <Header></Header>
    <router-view/>
  </div>
</template>

<script>
import Header from './components/Header'

export default {
  name: 'App',
  components: { Header }
}
</script>

<style>
body, html {
  margin-top: 0;
  padding-top: 0;
}
#app {
  font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
  margin: 0 auto;
  max-width: 900px;
  padding: 0 5%;
}
</style>
