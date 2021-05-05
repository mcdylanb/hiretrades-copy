<template>
  <div>
    <header>
      <div>Logo</div>
      <div>
        <ul>
          <li>Trades</li>
          <li>Cost Guides</li>
          <li>Blogs</li>
        </ul>
      </div>
      <div>
        <ul>
          <li>Get Quotes</li>
          <li>Register Business</li>
          <li>Login</li>
        </ul>
      </div>
    </header>

    <div>
      <form action="">
        <h1>Australia's most trusted trades provider</h1>
        <div class="form-example">
          <label for="name">What trade do you need?</label>
          <input type="text" name="name" id="name" required />
        </div>
        <div class="form-example">
          <label for="name">Postcode or Suburb</label>
          <input type="text" name="name" id="name" required />
        </div>
        <input type="button" value="post a job" />
      </form>
    </div>

    <footer>
      <div>LOGO</div>
      <div>NAV</div>
      <div>Download Our Apps</div>
    </footer>
  </div>

  <!-- <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div> -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: "App",
  components: {
    // HelloWorld
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
