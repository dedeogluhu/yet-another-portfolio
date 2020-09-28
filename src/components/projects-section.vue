<template>
  <section id="projects">
    <h1>Projects</h1>

    <div class="cards">
      <div class="card" v-for="project in projects" :key="project">
        <h2>{{ project.name }}</h2>
        <p class="card-text">
          {{ project.text }}
        </p>
        <div class="card-footer">
          <a class="card-link" :href="project.source">Source</a>
          <a class="card-link-gray" :href="project.live">Live Demo</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "projects",

  data: () => {
    return {
      projects: [
        {
          name: "Dedeogluhu",
          text: "Lorem Ipsum Dolor Sit Amet.",
          source: "https://github.com/dedeogluhu",
          live: "https://github.com/dedeogluhu",
        },
        {
          name: "Project2",
          text: "Lorem Ipsum Dolor Sit Amet.",
          source: "https://github.com/dedeogluhu",
          live: "https://github.com/dedeogluhu",
        },
        {
          name: "Project3",
          text: "Lorem Ipsum Dolor Sit Amet.",
          source: "https://github.com/dedeogluhu",
          live: "https://github.com/dedeogluhu",
        },
        {
          name: "New Project",
          text: "Lorem Ipsum Dolor Sit Amet.",
          source: "https://github.com/dedeogluhu",
          live: "https://github.com/dedeogluhu",
        },
      ],
    };
  },
};
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
  margin-top: 50px;
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