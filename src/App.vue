<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> 
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
 
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  background-color:lightgrey;
}

#nav a {
  font-weight: bold;
  color: olive;
  font-family:sofia;
  margin-left:20px;
}

#nav a.router-link-exact-active {
  color: purple;
}
</style>
