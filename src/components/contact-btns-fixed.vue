<template>
  <div id="links">
    <a href="https://github.com/dedeogluhu"
      ><img src="../assets/logo-github.png" id="github" class="logo"
    /></a>
    <a href="https://linkedin.com/in/dedeogluhu"
      ><img src="../assets/logo-linkedin.png" id="linkedin" class="logo"
    /></a>
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
  background: white;
  border: none;
  border: 5px solid black;
}

.logo:hover {
  background: orange;
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