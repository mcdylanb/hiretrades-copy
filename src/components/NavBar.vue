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
          <li class="action-button"><a href="">Register Business</a></li>
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
    display: flex;

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
}
ul li {
  list-style: none;
  padding: 0 1rem;
}
#right-group ul {
  display: flex;
}
</style>
