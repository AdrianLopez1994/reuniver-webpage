<template>
  <div id="app">
    <div>
      <p>
        Aquí irá el menú superior
      </p>
    </div>
    <WhoSection sectionType=""/>
  </div>
</template>

<script>
import WhoSection from './components/WhoSection.vue'

export default {
  name: 'App',
  components: {
    WhoSection
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
