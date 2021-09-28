<template>
  <div id="hero">
    <h1 id="hero_title">Hero Title</h1>
    <button id="hero_button">cliccami!</button>
  </div>
</template>

<script>
  export default {
    name: 'Hero'
  }
</script>

<style scoped lang="scss">
  #hero_title {
    color: white;
    font-size: 5rem;
  }
  #hero_button {
    background-color: red;
    border: transparent;
    border-radius: .9rem;
    padding: .5rem 1rem;
    cursor: pointer;
    color: white;
    font-size: 1rem;
    margin-top: 1rem;
  }
  #hero {
    background-image: url('../assets/jack-anstey-XVoyX7l9ocY-unsplash.jpg');
    background-position: center;
    background-size: cover;

    padding: 12rem 4rem;
    text-align: left;
  }
</style>