<template>
  <div id="top-bar" class="navbar">
    <div class="navbar-container">
      <div class="navbar-section navbar-left">
        <span>ACME Ltd.</span>
      </div>
      <div class="navbar-section navbar-right">
        <span>Welcome, James!</span>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'top-bar',
  };
</script>

<style lang="scss" scoped>
  @import './src/assets/scss/components/navigation';
</style>