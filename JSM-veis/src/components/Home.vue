<script>
export default {    name: "Home"   }
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

    
}

.Inputs {
    margin-left: 98vh;
    margin-bottom: 15vh;
}

input {
    height: 5vh;
    margin-bottom: 30px;
    border-radius: 30px;
    display: block;


}

.Cadastrar {
    margin-top: 30px;
    margin-left: 13px;
    border-radius: 30px;
    height: 50px;
    width: 150px;
    
}

.input_movel {
    margin-top: 8vh;
    margin-left: ;
}
</style>
