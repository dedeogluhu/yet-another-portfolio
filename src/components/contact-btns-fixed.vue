<template>
  <div id="app">
    <div id="links">
      <a href="https://github.com/dedeogluhu"
        ><img src="../assets/logo-github.png" id="github" class="logo"
      /></a>
      <a href="https://linkedin.com/in/dedeogluhu"
        ><img src="../assets/logo-linkedin.png" id="linkedin" class="logo"
      /></a>
    </div>
  </div>
</template>

<script>
export default { name: "App" };
</script>

<style scoped>
#links {
  position: fixed;
  right: 0;
  top: 80vh;
  display: flex;
  flex-direction: column;
}

.logo {
  margin: 0;
  transition: 0.5s;
  border-radius: 10px;
}

.logo:hover {
  background: rgba(0, 0, 0, 0.15);
}

#github {
  width: 50px;
}
#linkedin {
  width: 50px;
}
</style>