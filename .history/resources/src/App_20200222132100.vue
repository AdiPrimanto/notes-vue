<template>
  <div id="app">
    <!-- kiri -->
    <div class="kiri">
      <div class="logo">
        <a rel="stylesheet" href="https://google.com">
          <h2>Happy</h2>
          <span>Notes</span>
        </a>
      </div>
    </div>
    <!-- kanan -->
    <div class="kanan">
      <div class="frame-notes">
        <button @click="newNotes" class="bg-success btn btn-new-note">
          + Note Baru
        </button>
      </div>
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
