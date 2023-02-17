<template>
  <div class="header">
    <router-link to="/">
      <span class="logo">LOGO</span>
    </router-link>
  </div>
</template>

<style scoped lang="scss">
  .header {
    background-color: var(--color-background);
    padding: var(--spacing-20) var(--spacing-10);
  } 
  .logo {
    color: var(--color-text);
  }
</style>