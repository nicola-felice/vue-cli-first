<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <myTitle id="title"/>
    <Hero/>
  </div>
</template>

<script>
import myTitle from './components/myTitle.vue';
import Hero from './components/Hero.vue';

export default {
  name: 'App',
  components: {
    myTitle,
    Hero
  }
}
</script>

<style lang="scss">
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
  #title {
    margin: 2rem 0;
  }
</style>
