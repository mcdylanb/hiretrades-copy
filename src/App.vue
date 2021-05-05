<template>
  <div>
    <NavBar />
    <Hero />

    <div>how hiretrades work</div>

    <div>Inspirational Panel</div>
    <div>What home owners are saying</div>
    <div>Downlaod the HIRETrades APP</div>
    <div>Our Top Trades</div>
    <Footer />
  </div>

  <!-- <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div> -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import NavBar from "./components/NavBar.vue";
import Hero from "./components/Hero.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    NavBar,
    Hero,
    Footer,
  },
};
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
