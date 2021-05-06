<template>
  <header>
    <div class="logo">Logo</div>
    <div class="space-between">
      <div id="left-group">
        <ul>
          <li><a href="">Trades</a></li>
          <li><a href="">Cost Guides</a></li>
          <li><a href="">Blogs</a></li>
        </ul>
      </div>
      <div id="right-group">
        <ul>
          <li><a href="">Get Quotes</a></li>
          <li ><a href="" class="action-button">Register Business</a></li>
          <li><a href="">Login</a></li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
header {
  position: sticky;
  height: 4rem;
  width: 100%;
  background-color: bleck;
  display: flex;
  align-items: center;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.0624);
}
.logo {
  padding: 4rem;
}
.space-between {
  width: 100%;
  justify-content: space-between;
  align-items: center;
  display: flex;
}
.action-button {
  background-color: none;
  color: var(--third-color);
  border: 2px solid var(--third-color);
  padding: 0.5rem;
  border-radius: 5px;
}

.action-button:hover {
    background-color: var(--third-color);
    color: white;
}

a {
  text-decoration: none;
  color: #666;
  font-size: 1.2rem;
  font-weight: 600;
}

a:hover {
  color: var(--third-color);
}

#left-group ul {
  display: flex;
  align-items: center;
}
ul li {
  list-style: none;
  padding: 0 1rem;
}
#right-group ul {
  display: flex;
  align-items: center;
}
</style>
