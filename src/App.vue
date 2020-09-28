<template>
  <div id="app">
    <navbar />
    <contactBtns />
    <main-section />
    <projectsSection />
    <contactSection />
    <footerSection />
  </div>
</template>

<script>
import navbar from "./components/navbar.vue";
import contactBtns from "./components/contact-btns-fixed.vue";
import mainSection from "./components/main-section.vue";
import projectsSection from "./components/projects-section.vue";
import contactSection from "./components/contact-section.vue";
import footerSection from "./components/footer-section.vue";

export default {
  name: "App",
  components: {
    navbar,
    contactBtns,
    mainSection,
    projectsSection,
    contactSection,
    footerSection,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}

section {
  border-bottom: 1px solid white;
}
</style>
