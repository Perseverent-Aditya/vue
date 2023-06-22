<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div class="github">
      <p>This is a github page</p>
    </div>
    <div class="class">
      <p>This is amazingt</p>
      <p>dev branch is created</p>
      <div>
        <p>This is feature 1</p>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
