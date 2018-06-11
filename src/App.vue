<template>
  <div id="app">
    <TopBar/>
    <MainSection/>
    <BottomBar/>
  </div>
</template>

<script>
  import TopBar from './components/TopBar';
  import MainSection from './components/MainSection';
  import BottomBar from './components/BottomBar';
  export default {
    name: 'GIF Animations',
    components: {
      TopBar,
      MainSection,
      BottomBar
    }
  }
</script>

<style lang="scss">
  @import './src/assets/scss/components/base';
</style>
