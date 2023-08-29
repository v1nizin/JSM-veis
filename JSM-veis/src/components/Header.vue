<script>
export default {    name: 'Header'  }
</script>

<template>
    <div class="Header">
        <h1 class="JSMoveis">JS Móveis</h1>
        <h2 class="Pessoal">Pessoal </h2>
        <button><h3>Perfil</h3></button>
        <button class="BM"><h3>Móveis</h3></button>
        <h3 class="Logout">Logout</h3>
   </div>
</template>

<style>

    .Header {
        border-right: 3px solid black;
        color: black;
        position: fixed;
    }

    .JSMoveis {
        margin-right: 50px;
    }

    .Pessoal {
        margin-top: 30px;
    }



    .Logout {
        margin-top: 67.5vh;
        margin-left: 5vh;
    }

</style>