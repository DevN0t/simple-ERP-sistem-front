<script setup>

</script>

<template>  
  <div class="sidebar">
    <h1 class="logo">AgPortal</h1>
    <a class="sidebar_item">CADASTRO</a>
    <a class="sidebar_item">PEDIDO</a>
    <a class="sidebar_item">RELATORIO</a>
  </div>
</template>

<style scoped>
  .sidebar{
    margin-top: 3rem;
    display: flex;
    flex-direction: column;
    color: white;
    font-size: 3rem;
    
  }
  .sidebar_item{
    padding: 1rem;
    margin-bottom: .5rem;
    border-radius: 0px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-weight: 300;
  }
  .logo{
    font-size: 5rem;
    padding: 1rem;
    display: flex;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;

    justify-content: center;
    margin-bottom: 30rem;
  }
  .sidebar_item:hover{
    cursor: pointer;
    font-weight: 400;
  }

 
</style>
