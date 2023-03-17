<script setup lang="ts">
import SideBar from './components/SideBar.vue'
</script>

<template>
  <div class="sidebar">
    <SideBar />
  </div>

  <RouterView />
</template>

<style scoped>

.sidebar {
  line-height: 1.5;
  min-width: 20vw;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 2rem;
}

@media (min-width: 1024px) {
  .logo {
    margin: 0 2rem 0 0;
  }

  .sidebar {
    margin: auto;
    place-items: flex-start;
    flex-wrap: wrap;
    flex: 1 1 0;
    padding-right: 6rem;
  }
}
</style>
