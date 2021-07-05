<template>
  <div class="hello">
    <h1>{{ titolo }}</h1>
    <h2>{{titolo2}}</h2>
  </div>
</template>

<script>
export default {
  name: 'Title',
  props: {
    titolo: String, //nota per me : se metto int e in App.vue metto una stringa il compilatore si incazza di brutto
    titolo2: String
  },
  methods: {
    
  },
  mounted() {
    console.log("un console log vale piu di mille parole")
    // alert("leggi la console")
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
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
