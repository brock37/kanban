<template>
  <div class="app">
    <!--<div class="nav justify-content-center">
      <span class="nav-item"><router-link to="/" class="nav-link">Home</router-link></span>
      <span class="nav-item"><router-link to="/about" class="nav-link">About</router-link></span>
    </div>!-->
    <nav class="navbar sticky-top bg-primary justify-content-between">
      <h1 class="nav-brand text-light">My project</h1>

      <img src="./assets/account.png" alt="Profil picture" class="rounded-circle account">
    </nav>

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
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
