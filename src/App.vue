<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> 
      <router-link to="/about">About</router-link>
      <router-link to="/contact">Contact Us</router-link> 
      <router-link to="/login">Login</router-link>
      <router-link to="/todos">Todos</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
body{
  margin:unset;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
#nav {
  padding: 30px;
  margin:0px;
  text-align: right;
  background-color:#c3dfd3;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  margin:20px;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>