<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default{
    name: "Banner" //nomeando o componente
}
</script>

<style scoped>
    #main-banner{
        background-image: url('img/burger.jpg');
        background-position: 0 -500px; /* Subindo um pouco para aparecer mais o hamburguer do banner */
        background-size: cover; /* Deixa a img aparecendo o máx possível na área disponível */
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1{
        color:#fff;
        text-align: center;
        font-size: 60px;
        background-color: #222;
        padding: 20px 40px;
    }
</style>