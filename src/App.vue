<script setup>
import Welcome from './components/Welcome.vue'
import NavBar from './components/NavBar.vue'
</script>

<template>
  <main class="mainContainer">
    <NavBar />
    <Welcome />
  </main>
</template>

<style scoped>
.mainContainer {
  display: flex;
  flex-direction: column;
  height: 100vh;
}
.mainContainer > :first-child {
  flex-shrink: 0;
}
.container > :last-child {
  flex-grow: 1;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
