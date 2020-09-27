<template>
  <section id="contact">
    <h1>Contact</h1>

    <h2 id="mail">
      You can reach me at my e-mail
      <a href="mailto:huseyin_dedeoglu1@outlook.com" class="text-orange"
        >here</a
      >
    </h2>

    <h2 id="social">or here <span id="arrow" class="text-orange">=></span></h2>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
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
  top: 283vh;
  right: 5vw;
  font-size: 50px;
}

#arrow {
  font-size: 50px;
}

.text-orange {
  color: orange;
}
</style>