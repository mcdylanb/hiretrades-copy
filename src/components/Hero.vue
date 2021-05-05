<template>
    <div>
        <h1>Australia's most trusted trades provider</h1>
      <form action="">
        <div class="form-example">
          <label for="name">What trade do you need?</label><br>
          <input type="text" name="name" id="name" required />
        </div>
        <div class="form-example">
          <label for="name">Postcode or Suburb</label><br>
          <input type="text" name="name" id="name" required />
        </div>
        <input type="submit" value="post a job" />
      </form>
    </div>
</template>

<script>
export default {
}
</script>

<style scoped>
*{
    --main-color: #475f7b;
    --sec-color: #ff5b5c;
    font-family: Rubik,Helvetica,Arial,serif;
    text-align: center;
    display: flex;
    flex-direction: column;
}
h1, label {
    color: var(--main-color);
}
h1 {
    font-size: 4rem;
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
    
}

form {
    justify-content: space-evenly;
    align-items: center;
    align-content: center;
}
</style>