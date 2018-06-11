<template>
  <section id="main-section">
    <h1 class="section-title">Nice Pictures</h1>
    <div class="main-container">
      <div v-for="(gif, index) in gifs" v-bind:key="index" class="item">
        <div class="item-content">
          <img v-bind:src="gif.gifurl" class="item-image">
          <div class="item-content-text">
            <div class="item-description">
              {{ gif.title }}
            </div>
            <div class="item-button-wrapper">
              <button class="item-button">Go</button>
            </div>
          </div>
        </div>
      </div>
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
  @import './src/assets/scss/components/grid';
</style>