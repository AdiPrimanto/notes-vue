<template>
  <div id="app">
    <!-- kiri -->
    <div class="kiri">
      <div class="logo">
        <a rel="stylesheet" href="https://google.com">
          <h2>Happy Notes</h2>
          <span></span>
        </a>
      </div>
    </div>
    <!-- kanan -->
    <div class="kanan">

    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
