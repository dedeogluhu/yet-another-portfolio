<template>
  <div id="app">
    <navbar />
    <contactBtns />
    <main-section />
  </div>
</template>

<script>
import navbar from "./components/navbar.vue";
import contactBtns from "./components/contact-btns-fixed.vue";
import mainSection from "./components/main-section.vue";

export default {
  name: "App",
  components: {
    navbar,
    contactBtns,
    mainSection,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
