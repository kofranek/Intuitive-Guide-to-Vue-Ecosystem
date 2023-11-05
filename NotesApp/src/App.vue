<template>
  <main>
    <div class="container">
      <header>
        <h1>Notes</h1>
        <button>+</button>
        <div class="card-container">
          <p class="main-text"></p>
          <p class="date"></p>
        </div>
      </header>
    </div>
  </main>
</template>

<style scoped>
main {
  height: 100vh;
  width: 100vw;
}
.container {
  max-width: 1000px;
  padding: 10px;
  margin: 0,auto;
}
</style>

header {
  display:flex;
  justify-content: space-between;
  align-items:center;
}