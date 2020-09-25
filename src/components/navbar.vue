<template>
  <div id="navbar">
    <header id="header">
      <nav id="nav">
        <h3 id="logo">
          <span class="text-orange">D</span>edeoglu<span class="text-orange"
            >h</span
          >u
        </h3>
        <ul id="links">
          <li>
            <a class="nav-btn" href="#home">Home</a>
          </li>
          <li>
            <a class="nav-btn" href="#projects">Projects</a>
          </li>
          <li>
            <a class="nav-btn" href="#contact">Contact</a>
          </li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<script>
export default {
  name: "navbar",
  props: {},
};
</script>

<style scoped>
a {
  text-decoration: none;
  color: orange;
}

ul {
  list-style: none;
}

#logo {
  color: white;
  margin: auto 0;
  font-size: 25px;
  flex: 2;
  cursor: grab;
}

#nav {
  display: flex;
  justify-content: space-around;
  padding: 25px;
  background: linear-gradient(-90deg, #16222a 0%, #3a6073 100%);
}

#links {
  display: flex;
  justify-content: space-between;
}

.nav-btn {
  margin: 5vh;
  border: solid 1px orange;
  padding: 5px 20px;
  border-radius: 13px;
  transition: 0.5s;
  font-size: 20px;
}

.nav-btn:hover {
  background-color: orange;
  color: #3a6073;
}

.text-orange {
  color: orange;
}
</style>