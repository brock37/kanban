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

<style lang="css">
.app {
  height: 100vh;
}

nav {
  height: 50px;
}

h1.nav-brand {
  font-size: 24px;
}

img.account {
  width: 36px;
  height: 36px;
}
</style>
