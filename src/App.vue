<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>

</script>

<style>


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}


#nav {
  font-weight: bold;
  color: #2c3e50;
}

.pestaña.router-link-exact-active{
  border-style: solid;
  border-color: #42b983;
  border-width: 1px;
  border-bottom: 0;
  border-radius: 3px;
 
}

#nav.router-link-exact-active {
  color: #42b983;
  padding: 1rem 2rem;
  border-style: solid;
  border-color: #42b983;
  border-width: 1px;
  border-bottom: 0;
  border-radius: 3px;
  
}
</style>
