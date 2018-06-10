<template>
  <section id="main-section">
    <div v-for="(gif, index) in gifs">
      <img v-bind:src="gif.gifurl">
      <span>{{ gif.title }}</span>
      <button>Go</button>
    </div>
  </section>
</template>

<script>
  import gifs from '../assets/static/gifs.json';
  export default {
    name: 'main-section',
    data() {
      return {
        gifs: gifs
      }
    }
  };
</script>

<style lang="scss" scoped>
  @import './src/assets/scss/components/navigation';
</style>