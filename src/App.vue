<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/challenge-1">Challenge 1</router-link> |
      <router-link to="/challenge-2">Challenge 2</router-link> |
      <router-link to="/challenge-3">Challenge 3</router-link> |
      <router-link to="/final">Final</router-link>
    </div>
    <router-view />
    <div class="flower">
      <img src="https://images.unsplash.com/photo-1613539246066-78db6ec4ff0f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1000&q=80" 
      alt="Flower1">
    </div>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
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

img {
  max-width: 100%;
  max-height: 100%;
}

.flower {
  height: 500px;
  width: 330px;
  position: absolute;
  bottom: 0%;
  left: 0%;
}
</style>
