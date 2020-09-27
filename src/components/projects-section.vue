<template>
  <section id="projects">
    <h1>Projects</h1>

    <div class="cards">
      <div class="card">
        <h2>Project 1</h2>
        <p class="card-text">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fuga,
          praesentium. Lorem ipsum dolor sit amet consectetur adipisicing elit.
          Vitae, illum. Corrupti vel est assumenda. Omnis reiciendis id
          similique architecto pariatur, labore optio odit dolorum obcaecati
          nobis temporibus iusto natus rem! Lorem ipsum dolor, sit amet
          consectetur adipisicing elit. Ratione, voluptas.
        </p>
        <div class="card-footer">
          <a class="card-link" href="https://github.com/dedeogluhu">Source</a>
          <a class="card-link-gray" href="https://github.com/dedeogluhu"
            >Live Demo</a
          >
        </div>
      </div>
      <div class="card">
        <h2>Project 2</h2>
        <p class="card-text">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Saepe cum,
          tempore asperiores libero nam cumque hic voluptates pariatur quod,
          laudantium ea nesciunt eius? Molestias cumque velit alias omnis porro
          aut odio magnam assumenda, distinctio harum veniam magni repellendus!
          Quibusdam dolores voluptatum perspiciatis magnam impedit ratione,
          voluptas recusandae. Laborum, dolor! Iure! Lorem ipsum dolor, sit amet
          consectetur adipisicing elit. Fuga, praesentium. Lorem ipsum dolor sit
          amet consectetur adipisicing elit. Praesentium sapiente officiis eos
          aperiam ducimus deleniti qui consequuntur porro nisi numquam, vel esse
          quas animi distinctio error modi beatae? Accusamus aliquam assumenda
          reiciendis veritatis consequatur in dolor ad debitis magnam quasi
          exercitationem nam tempora temporibus dolorum, ipsa aperiam
          reprehenderit pariatur praesentium!
        </p>
        <div class="card-footer">
          <a class="card-link" href="https://github.com/dedeogluhu">Source</a>
          <a class="card-link-gray" href="https://github.com/dedeogluhu"
            >Live Demo</a
          >
        </div>
      </div>
      <div class="card">
        <h2>Project Title</h2>
        <p class="card-text">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fuga,
          praesentium.
        </p>
        <div class="card-footer">
          <a class="card-link" href="https://github.com/dedeogluhu">Source</a>
          <a class="card-link-gray" href="https://github.com/dedeogluhu"
            >Live Demo</a
          >
        </div>
      </div>
      <div class="card">
        <h2>Project Title</h2>
        <p class="card-text">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fuga,
          praesentium.
        </p>
        <div class="card-footer">
          <a class="card-link" href="https://github.com/dedeogluhu">Source</a>
          <a class="card-link-gray" href="https://github.com/dedeogluhu"
            >Live Demo</a
          >
        </div>
      </div>
      <div class="card">
        <h2>Project Title</h2>
        <p class="card-text">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fuga,
          praesentium.
        </p>
        <div class="card-footer">
          <a class="card-link" href="https://github.com/dedeogluhu">Source</a>
          <a class="card-link-gray" href="https://github.com/dedeogluhu"
            >Live Demo</a
          >
        </div>
      </div>

      <!-- Fazlalık -->

      <div class="card">
        <h2>Project Title</h2>
        <p class="card-text">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fuga,
          praesentium.
        </p>
        <div class="card-footer">
          <a class="card-link" href="https://github.com/dedeogluhu">Source</a>
          <a class="card-link-gray" href="https://github.com/dedeogluhu"
            >Live Demo</a
          >
        </div>
      </div>
      <div class="card">
        <h2>Project Title</h2>
        <p class="card-text">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fuga,
          praesentium.
        </p>
        <div class="card-footer">
          <a class="card-link" href="https://github.com/dedeogluhu">Source</a>
          <a class="card-link-gray" href="https://github.com/dedeogluhu"
            >Live Demo</a
          >
        </div>
      </div>
      <div class="card">
        <h2>Project Title</h2>
        <p class="card-text">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fuga,
          praesentium.
        </p>
        <div class="card-footer">
          <a class="card-link" href="https://github.com/dedeogluhu">Source</a>
          <a class="card-link-gray" href="https://github.com/dedeogluhu"
            >Live Demo</a
          >
        </div>
      </div>
      <div class="card">
        <h2>Project Title</h2>
        <p class="card-text">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fuga,
        </p>
        <div class="card-footer">
          <a class="card-link" href="https://github.com/dedeogluhu">Source</a>
          <a class="card-link-gray" href="https://github.com/dedeogluhu"
            >Live Demo</a
          >
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default { name: "projects" };
</script>

<style>
#projects {
  height: 100vh;
  background: linear-gradient(-90deg, #16222a 0%, #3a6073 100%);
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  color: white;
}
/* 

body {
  background: #3a6073;
  height: 100vh;
  margin: 0;
  display: grid;
  place-items: center;
}
 */
.cards {
  display: flex;
  overflow: auto;
  width: 65vw;
  padding: 2rem 1rem 3rem 10px;
  border: 2px solid orange;
  border-radius: 10px;
  color: black;
}

.card {
  background: #fcb93e;
  border-radius: 1rem;
  padding: 2rem;
  transition: 0.2s;
  box-shadow: 4px 4px 15px 2px rgba(0, 0, 0, 0.7);
}

.card-text {
  height: 220px;
  width: 200px;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
}

.card-link {
  text-decoration: none;
  background-color: royalblue;
  color: white;
  padding: 5px 10px;
  border-radius: 1rem;
}

.card-link-gray {
  text-decoration: none;
  background-color: gray;
  color: white;
  padding: 5px 10px;
  border-radius: 1rem;
}

.card-link:hover {
  background-color: #6185f3;
}

.card-link-gray:hover {
  background-color: #a09e9e;
}

.card:not(:first-child) {
  margin-left: -4rem;
}

.card:hover,
.card:focus-within {
  transform: translateY(-1rem);
  color: #fcb93e;
  background: black;
}

.card:hover ~ .card {
  transform: translateX(4rem);
}

.cards::-webkit-scrollbar {
  width: 15px;
  height: 15px;
}

.cards::-webkit-scrollbar-thumb {
  background-color: orange;
  border-radius: 10px;
  transition: 0.5s;
}

.cards::-webkit-scrollbar-thumb:active {
  background-color: #312c3b;
}
</style>