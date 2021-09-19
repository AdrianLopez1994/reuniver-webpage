<template>
  <div id="app">
    <div>
      <p>
        Aquí irá el menú superior
      </p>
    </div>
    <SectionTemplate sectionType=""/>
  </div>
</template>

<script>
import SectionTemplate from './components/SectionTemplate.vue'

export default {
  name: 'App',
  components: {
    SectionTemplate
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
