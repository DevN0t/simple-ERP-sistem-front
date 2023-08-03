<script setup>
import CadastroItem from './components/CadastroItem.vue';
import NavBarItem from './components/NavBarItem.vue'
</script>

<template>
  
  <div class="app">
    <div class="navBar">
      <NavBarItem/>
    </div>
    <div class="main">
      <CadastroItem/>
    </div>
  </div>
</template>

<style scoped>
.app {
  padding: 0rem;
  background-color: #5c50ff;
  display: grid;
  grid-template-columns: 15% 85%;

}

.navBar {
  min-height: 1080px;
}
</style>
