<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/projects">Projects</router-link> |
      <router-link to="/contact">Contact</router-link>
      <br>
      <a href="https://github.com/wlw-code" target="_blank"><img alt="GitHub" src="./assets/GitHub-Mark-32px.png" id="githubLogo" width="24"/></a>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding-top: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42e0f5;
}

#githubLogo {
  margin-top: 10px;
  border: 1px solid #2c3e50;
  border-radius: 15px;
}
</style>
