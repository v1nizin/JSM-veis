<script>
export default {    name: 'Nav'    }
</script>

<template>
  <nav class="navbar">
    <ul>
      <li><router-link to="/">Página Inicial</router-link></li>
      <li><router-link to="/sobre">Sobre</router-link></li>
      <li><router-link to="/contato">Contato</router-link></li>
    </ul>
    
    <div class="search-bar">
      <input class="barradepesquisa" type="text" v-model="searchQuery" placeholder="Pesquisar">
    </div>
    <button class="pesquisa" @click="search">Buscar</button>
  </nav>
</template>

<style>
.navbar {
  display: flex;
  justify-content: space-between; 
  align-items: center; 
  padding: 10px 20px;
  background-color: #3c4daf;
  color: white;
  margin-bottom: 900vh;
  margin-right: 9vh;
}
ul {
  list-style: none;
  display: flex;
  gap: 60px; 
  margin-left: 10px;
  
}

ul li a {
  text-decoration: none;
  color: white;
}

.barradepesquisa {
  margin-top: 9px;
  margin-left: 100vh;
}

.pesquisa {
  margin-left: 14px;
  height: 50px;
  
}


</style>