<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">
        <div class="ball">
           <img alt="Vue logo" src="./assets/breezy.svg">
        </div>
      </router-link>
      <router-link to="/todo">
        <div class="ball">
           <img alt="Vue logo" src="./assets/breezy.svg">
        </div></router-link>
      <router-link to="/breezy">  <div class="ball">
           <img alt="Vue logo" src="./assets/breezy.svg">
        </div></router-link>
      <router-link to="/dontforget">
        <div class="ball">
           <img alt="Vue logo" src="./assets/breezy.svg">
        </div>
      </router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.ball {
  height: 200px;
  width: 200px;
  border-radius: 100px;
  background: #2c3e50;
}
</style>
