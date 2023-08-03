<script setup>


</script>

<template>
    <div class="main">
        <button class="cadastro_escolha">Cliente</button>
        <button class="cadastro_escolha">Produto</button>
    </div>


</template>

<style scoped>
    .main{
    display: flex;
    justify-content: center;
    background-color: #f3f3f3; 
    color: rgb(65, 65, 65);
    font-size: 3rem;
    height: 100%;
    border-top-left-radius: 10px;
    border-bottom-left-radius: 40px;
    gap: 4rem;

    }

    .cadastro_escolha{
        
        display: flex;
        padding: 1rem 30rem;
        border-radius: 0rem 0rem 1rem 1rem;
        height: fit-content;
        width: fit-content;
        border: solid 0;
        background-color: #5c50ff;
        color: #f3f3f3;
        font-weight: 500;
        font-size: 4rem;
        cursor: pointer;
    }

    .cadastro_escolha:hover {
        background-color: #6a5fff;

    }
</style>

