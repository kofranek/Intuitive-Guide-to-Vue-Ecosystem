<template>
  <main>
    <div class="container">
      <header>
        <h1>Notes</h1>
        <button>+</button>
      </header>
        <div class="card-container">
          <card class="card"> 
            <p class="main-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem soluta, possimus numquam aspernatur voluptatem cum.</p>
            <p class="date">04/27/6853</p>
          </card>
          <card class="card"> 
            <p class="main-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem soluta, possimus numquam aspernatur voluptatem cum.</p>
            <p class="date">04/27/6853</p>
          </card>
        </div>
    </div>
  </main>
</template>

<style scoped>
main {
  height: 100vh;
  width: 100vw;
  /* background-color: aqua; */
}
.container {
  max-width: 1000px;
  padding: 10px;
  margin: 0, auto; /* nahoře, dole: 0, vpravo,vlevo:position: ; stejně*/
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

h1 {
  font-weight: bold;
  margin-bottom: 25px;
  font-size: 75px;
}
button {
  border: none;
  padding: 10px;
  width: 50px;
  cursor: pointer;
  background-color: rgb(21, 20, 20);
  border-radius: 100%;
  color: white;
  font-size: 20px;
}

.date{
  font-size:12.5px;
  font-weight:bold;
}

card {
  width:225px;
  height:225px;
  background-color:rgb(237,182,44);
  padding: 10px;
  border-radius:15px;
  display:flex;
  flex-direction:column;
  justify-content:space-between;
  margin-right: 20px;
  margin-bottom:20px;
}

.card-container {
  display:flex;
  flex-wrap:wrap;

}
</style>