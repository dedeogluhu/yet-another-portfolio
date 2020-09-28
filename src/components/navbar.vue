<template>
  <div id="navbar">
    <nav id="nav">
      <ul id="links">
        <li>
          <a class="nav-btn" href="#projects">Projects</a>
        </li>

        <li>
          <h3 id="logo">
            <a href="#home">
              <span class="text-orange">D</span>edeoglu<span class="text-orange"
                >h</span
              >u
            </a>
          </h3>
        </li>

        <li>
          <a class="nav-btn" href="#contact">Contact</a>
        </li>
      </ul>
    </nav>
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
  color: white;
}

ul {
  list-style: none;
}

#navbar {
  position: fixed;
  top: 0;
  right: 0;
  left: 0;
  border-bottom: 1px solid white;
  z-index: 1;
}

#logo {
  color: white;
  margin: auto 0;
  font-size: 28px;
  flex: 2;
}

#nav {
  padding: 25px;
  background: linear-gradient(-90deg, #16222a 0%, #3a6073 100%);
}

#links {
  display: flex;
  justify-content: space-around;
}

.nav-btn {
  margin: 5vh;
  border: solid 2px orange;
  padding: 8px 15px;
  border-radius: 13px;
  transition: 0.3s;
  font-size: 20px;
}

.nav-btn-contact {
  margin: 5vh;
  border: solid 2px orange;
  padding: 10px 20px;
  border-radius: 13px;
  transition: 0.3s;
  font-size: 20px;
  background: orange;
  color: #000;
}

.nav-btn-contact:hover {
  background: none;
  color: white;
}

.nav-btn:hover {
  background-color: orange;
  color: #000;
}

.text-orange {
  color: orange;
}
</style>