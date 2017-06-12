<template>
  <div id="app">
    <app-navbar></app-navbar>
    <img src="./assets/logo.png">
    <router-view></router-view>
    <app-footer></app-footer>
  </div>
</template>

<script>
  import NavBar from './components/NavBar.vue';
  import Foot from './components/Foot.vue';

  export default {
    name: 'app',
    components: {
      appNavbar: NavBar,
      appFooter: Foot
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

  }
</style>
