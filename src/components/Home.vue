<script>
export default {    name: "Home"    }
</script>

<template>
    <div class="Inputs">
            <h1 class="h1_home">Cadastro de Móveis</h1>
    
            <input class="input_movel" type="text" placeholder="Móvel">
            
            <input type="text" placeholder="Cor">
            
            <input type="text" placeholder="Tamanho">
            
            <input type="text" placeholder="Código do Produto">

            <button class="Cadastrar">Cadastrar</button>
    </div>    
</template>

<style>
.h1_home {
    margin-top: 10vh;
    margin-left: vh;
}
.Inputs {
    margin-bottom: 50vh;
    margin-right: 30vh;
}

input {
    height: 5vh;
    margin-bottom: 30px;
    border-radius: 30px;
    margin-left: 30vh;
}

.Cadastrar {
    margin-top: 60px;
    margin-left: 300px;
    border-radius: 30px;
    height: 50px;
    width: 150px;
    
}

.input_movel {
    margin-top: 3.8vh;
}
</style>
