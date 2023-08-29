<script>
export default {    name:'NavBarLateral' }
</script>

<template>
  <aside class="sidebar">
    <ul>
      <li><router-link to="/"><h1>Móveis JS</h1></router-link></li>
      
    </ul>
  </aside>
</template>


<style>
.sidebar {
  position: fixed;
  top: 0;
  left: 0;
  width: 180px;
  height: 100%;
  background-color: #5636ac;
  color: white;
  overflow-y: auto;
  border-right: 3px solid rgb(49, 39, 39);

}

ul {
  list-style: none;
  padding: 0;
}

li {
  padding: 10px 20px;
}

li a {
  text-decoration: none;
  color: white;
}
</style>
