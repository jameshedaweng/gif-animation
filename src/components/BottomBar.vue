<template>
  <div id="bottom-bar" class="navbar">
    <div class="navbar-container">
      <div class="navbar-section navbar-left">
        <div class="navbar-text-wrapper">
          <span class="online-indicator"></span>
          <span class="navbar-text">8 users online</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'bottom-bar',
  };
</script>

<style lang="scss" scoped>
  @import './src/assets/scss/components/navigation';
</style>