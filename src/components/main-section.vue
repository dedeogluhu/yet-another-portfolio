<template>
  <section id="home">
    <h1 id="main-header">Hi There<a href="#" id="hello">👋</a></h1>

    <h3 class="main-para">
      I'm a fullstack web developer who loves to make life easier
    </h3>

    <h4 class="main-para">
      Check my <a href="#" class="text-orange"> resume</a>(to be added)
    </h4>
  </section>
</template>

<script>
export default {
  name: "main-section",
};
</script>

<style scoped>
a {
  text-decoration: none;
}
ul {
  list-style: none;
  color: white;
}
#home {
  height: 100vh;
  background: linear-gradient(-90deg, #16222a 0%, #3a6073 100%);
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

#main-header {
  color: white;
}

#hello {
  cursor: grab;
}

.main-para {
  margin-top: 20px;
  color: white;
}

.text-orange {
  color: orange;
}
</style>