<template>
  <div class="main-section-div">
    <h2> {{ $t('titles.who') }} </h2>
    <div class=""></div>
    <hr style="width:80%">
  </div>
</template>

<script>
export default {
  name: 'WhoSection',
  props: {
    sectionType: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
