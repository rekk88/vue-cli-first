<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Hero />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Title 
      titolo="La mia primissima app in Vue CLI(che emozione vedere che funziona)" 
      titolo2="sono un h2 :D"
    />
  </div>
</template>

<script>
//ogni import deve avere un export 
// import HelloWorld from './components/HelloWorld.vue' 
import Title from './components/Title.vue'
import Hero from './components/Hero.vue'
export default { //questo export corrisponde a import in main.js riga 2
  name: 'App',
  components: {
    // HelloWorld,
    Title,
    Hero 
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  /*toglie i margini orizz. ma c'è comunque uno spazio bianco  */
  margin-left: 0;
  margin-right: 0;
}
</style>
