<template>
  <div>
    <NavBar />
    <Hero />

    <How/>

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
import How from "./components/How.vue";

export default {
  name: "App",
  components: {
    NavBar,
    Hero,
    Footer,How,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  --fourth-color: #e6eaee;
  --main-color: #475f7b;
  --sec-color: #ff5b5c;
  --third-color: #7468f0;
  font-family: Rubik, Helvetica, Arial, serif;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
