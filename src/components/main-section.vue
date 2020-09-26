<template>
  <div id="main">
    <h1 id="main-header">Hi There<a href="#">👋</a></h1>
  </div>
</template>

<script>
export default {
  name: "main-section",
};
</script>

<style>
a {
  text-decoration: none;
  cursor: grab;
}
ul {
  list-style: none;
  color: white;
}
#main {
  height: 100vh;
  background: linear-gradient(-90deg, #16222a 0%, #3a6073 100%);
  display: flex;
  justify-content: center;
  align-items: center;
}

#main-header {
  color: white;
}
</style>