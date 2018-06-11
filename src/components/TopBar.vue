<template>
  <div id="top-bar" class="navbar">
    <div class="navbar-container">
      <div class="navbar-section navbar-left">
        <div class="navbar-text-wrapper">
          <a class="navbar-brand" href="#">ACME Ltd.</a>
        </div>
      </div>
      <div class="navbar-section navbar-right">
        <div class="navbar-text-wrapper">
          <a class="navbar-link" href="#">Welcome, James!</a>
        </div>
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