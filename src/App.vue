<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
      </nav>
    </div>
  </header>

  <div>
    <RouterView />
  </div>
</template>

<script setup lang="ts">
  import { RouterLink, RouterView } from 'vue-router';

</script>
