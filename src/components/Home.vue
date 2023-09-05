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

<style scoped>

.Inputs {
    margin-left: 30px;
}

input {
    height: 5vh;
    margin-bottom: 30px;
    margin-top: 2px;
    border-radius: 30px;
    padding: 5px;
    display: flex;
    flex-direction: column;
   
}

.Cadastrar {
    margin-top: 60px;
    margin-left: 300px;
    border-radius: 30px;
    height: 50px;
    width: 150px;
}

.h1_home {
    margin-left: 255px;
}
</style>
