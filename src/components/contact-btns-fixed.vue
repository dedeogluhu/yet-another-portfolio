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
export default { name: "contact-btns" };
</script>

<style scoped>
#links {
  position: fixed;
  right: 0;
  top: 80vh;
  display: flex;
  flex-direction: column;
  border-radius: 10px;
}

.logo {
  margin: 0;
  transition: 0.5s;
  background: wheat;
  border: none;
}

.logo:hover {
  background: #e0e0e0c0;
}

#github {
  width: 50px;
  border-radius: 50%;
}
#linkedin {
  width: 50px;
  border-radius: 5px;
}
</style>