<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
import { store } from './vuex/store';

export default {
  name: 'App',
  store,
  methods: {}
};
</script>

<style>
body {
  margin: 0;
  padding: 0;
}

#app {
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
  /*-webkit-font-smoothing: antialiased;*/
  /*-moz-osx-font-smoothing: grayscale;*/
  /*color: #2c3e50;*/
  /*margin-top: 60px;*/
}
</style>
