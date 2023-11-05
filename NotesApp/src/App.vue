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

header {
  display:flex;
  justify-content: space-between;
  align-items:center;
}

h1 {
  font-weight: bold;
  margin-bottom: 25px;
  font-size:  75px;
}
button {
  border:none;
  padding: 10px;
  width:50px;
  height:
}
</style>

