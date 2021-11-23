<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld />
    <section id="productList">
      <productCard />
      <productCard />
      <productCard />
      <productCard />
      <productCard />
    </section>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import productCard from './components/productCard.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    productCard
  }
}
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center; 
  color: #2c3e50;
  margin-top: 60px;
}

#productList {
  display: flex;
  justify-content: space-evenly;
}
</style>
