<template>
    <div id="hero">
        <h1>Australia's most <br> trusted trades <br> provider</h1>
      <form action="">
        <div class="form-example">
          <label for="name">What trade do you need?</label><br>
          <input type="text" name="name" id="name" placeholder="e.g Plumber, Electricians" required />
        </div>
        <div class="form-example">
          <label for="name">Postcode or Suburb</label><br>
          <input type="text" name="name" id="name" placeholder="e.g Sydney"  required />
        </div>
        <input type="submit" value="Post a job" />
      </form>
    </div>
</template>

<script>
export default {
}
</script>

<style scoped>
*{
    text-align: center;
    display: flex;
    flex-direction: column;
}

#hero {
    margin: 0 22rem;
    height: 100vh;
    padding: 5rem;
    }
h1, label {
    color: var(--main-color);
}
h1 {
    font-size: 4rem;
    margin-bottom: 0;
}
label, input[type="text"] {
    text-align: left;
}
input[type="text"]{
    width: 464px;
    height:43px;
}
input[type="submit"]{
    color: white;
    background-color: var(--sec-color);
    border: none;
    border-radius: 5px;
    width: 341px;
    height:60px;
    cursor: pointer;
    
}
input[type="submit"]:hover{
    box-shadow: 0 5px 15px 2px var(--sec-color);
}
.form-example {
    padding: 2rem;
    }

form {
    justify-content: space-evenly;
    align-items: center;
    align-content: center;
}
</style>