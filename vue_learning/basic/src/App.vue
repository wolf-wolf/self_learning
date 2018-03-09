<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HookLearning></HookLearning>
  </div>
</template>

<script>
  import HelloWorld from './components/HelloWorld';
  import HookLearning from './components/HookLearning';

  export default {
    name: 'App',
    components: {
      HelloWorld,
      HookLearning
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
    margin-top: 60px;
  }
</style>
