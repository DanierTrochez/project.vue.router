<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link> |
      <br>
      <router-link to="/about">About</router-link>
      <br>
      <router-link to="/InicioView">InicioView</router-link>
      <br>
    <router-link to="/dashboar">dashboar</router-link>
    <br>
      <router-link to="/create">create</router-link>
      <br>
      <router-link to="/index">index</router-link>
      <br>
      <router-link to="/ubdate">ubdate</router-link>
      <br>
      <router-link to="/dashboart2">dashboart2</router-link>
      <br>
      <router-link to="/rol">rol</router-link>
      <br>
      <router-link to="/iniciosesion">iniciosesion</router-link>
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

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
