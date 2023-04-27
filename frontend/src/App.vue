<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
#app {
  padding: 20px;
  margin: 0 auto;
  max-width: 1024px;
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
