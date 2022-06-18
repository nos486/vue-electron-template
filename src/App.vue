<template>
  <div id="app">
    <button @click="setTitle">Set Title</button>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  mounted() {

  },
  methods :{
    setTitle(){
      window.electronAPI.setTitle("New Title")
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
