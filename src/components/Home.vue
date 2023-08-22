<script>
export default {    name: "Home"    }
</script>

<template>
    <div>
        <h1 class="h1_home">Cadastro de Móveis</h1>
    </div>
   
    <div class="Inputs">
        <input class="input_movel" type="text" placeholder="Móvel">
        
        <input type="text" placeholder="Cor">
        
        <input type="text" placeholder="Tamanho">
        
        <input type="text" placeholder="Código do Produto">

        <button>Cadastrar</button>

    </div>
</template>

<style>
.h1_home {
    margin-bottom: 80vh;
    margin-left: 500px;
    
}
.Inputs {
    margin-top: 30vh;
    margin-right: 50vh;
}
.input_movel {
    border-radius: 3px;
    
}
</style>
