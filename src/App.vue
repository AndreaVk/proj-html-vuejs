<template>
  <div id="app">
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>
    <Header/>
    <Main/>
  </div>
</template>

<script>

import Header from '../src/components/macro/Header.vue';
import Main from '../src/components/macro/Main.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
  }
}
</script>

<style lang="scss">
    @import './assets/style/global.scss'
</style>
