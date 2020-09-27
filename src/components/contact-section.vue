<template>
  <section id="contact">
    <h1>Contact</h1>

    <h2 id="mail">
      You can reach me at my e-mail
      <a href="mailto:huseyin_dedeoglu1@outlook.com" class="text-orange"
        >here</a
      >
    </h2>
    <div id="social">
      <h2 id="social-text">or here</h2>
      <h3 id="arrow" class="text-orange">=></h3>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap");

a {
  text-decoration: none;
}
#contact {
  height: 100vh;
  background: linear-gradient(-90deg, #16222a 0%, #3a6073 100%);
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  color: white;
}

#mail {
  padding-top: 50px;
}

#social {
  position: absolute;
  top: 280vh;
  right: 5vw;
}

#social-text {
  font-size: 40px;
}

#arrow {
  font-size: 50px;
  font-family: "Press Start 2P", cursive;
}

.text-orange {
  color: orange;
}
</style>