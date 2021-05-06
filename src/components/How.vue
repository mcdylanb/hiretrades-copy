<template>
  <div id="how">
    <h1>How HIREtrades works</h1>
    <div class="flex-wrapper-row">
      <div class="flex-wrapper-row">
        <h2>1</h2>
        <div class="flex-wrapper-column">
          <h3>Post a job</h3>
          <p>It takes 2 minutes</p>
        </div>
      </div>
      <div class="flex-wrapper-row">
        <h2>2</h2>
        <div class="flex-wrapper-column">
          <h3>Get quotes</h3>
          <p>Tradies get in touch</p>
        </div>
      </div>
      <div class="flex-wrapper-row">
        <h2>3</h2>
        <div class="flex-wrapper-column">
          <h3>Rate and review</h3>
          <p>Job complete. Leave feedback</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
h1 {
  font-size: 3rem;
  color: var(--main-color);
}

h2 {
  color: var(--third-color);
  font-size: 5rem;
  font-weight: 200;
}

#how {
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 60vh;
  width: 100%;
}
.flex-wrapper-row {
  display: flex;
  flex-direction: row;
  align-content: center;
  align-items: center;
}

.flex-wrapper-column {
  display: flex;
  flex-direction: column;
}
</style>