<template>
  <footer>
    <div id="brand">
      <h3>Logo</h3>
      <hr />
      <p>Australia's most trusted <br />trades provider</p>
    </div>
    <div class="footer-navi">
      <div>
        <h3>Customers</h3>
        <hr />
        <ul>
          <li><a href="">Get Quotes</a></li>
          <li><a href="">200+ Trades</a></li>
          <li><a href="">How it Works</a></li>
          <li><a href="">Trades Directory</a></li>
          <li><a href="">FAQS</a></li>
        </ul>
      </div>
      <div>
        <h3>Tradies</h3>
        <hr />
        <ul>
          <li><a href="">Register</a></li>
          <li><a href="">Login</a></li>
          <li><a href="">How it Works</a></li>
          <li><a href="">FAQs</a></li>
        </ul>
      </div>
      <div>
        <h3>HIREtrades</h3>
        <hr />
        <ul>
          <li><a href="">Contact Us</a></li>
          <li><a href="">Our Story</a></li>
          <li><a href="">Terms & Conditions</a></li>
          <li><a href="">Blogs</a></li>
          <li><a href="">Cost Guides</a></li>
        </ul>
      </div>
    </div>
    <div id="app-download">
<h3>
Download Our Apps
</h3>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
footer {
  background-color: var(--fourth-color);
  height: 60vh;
  width: 100%;
  display: flex;
  justify-content: center;
}

hr {
  border: 0;
  margin: 1rem 0;
  border-top: 1px solid #bfbfbf !important;
  width: 25%;
}

ul li {
  list-style: none;
  margin-bottom: 5px;
  text-align: left;
  padding-bottom: 1rem;
}

a {
  text-decoration: none;
  color: grey;
}

a:hover {
  color: var(--third-color);
  text-decoration: underline;
}

h3 {
  color: #444;
}

.footer-navi {
  display: flex;
  justify-content: space-between;
}

.footer-navi > div {
  padding: 0 2rem 2rem 2rem;
}

#brand,
#app-download,
.footer-navi {
  margin: 5rem;
}
</style>