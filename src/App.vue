<template>
  <div id="app">
    <div id="nav">
      <router-link :to="{name:'Home'}">Home</router-link> |
      <router-link :to="{name:'About'}">About</router-link> |
      <router-link :to="{name:'Tareas'}">Tareas</router-link> |
      <router-link :to="{name:'Peliculas'}">Películas</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  margin-bottom: 20px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  padding: 0 20px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
