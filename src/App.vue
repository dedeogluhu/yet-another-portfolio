<template>
  <navbar />
</template>

<script>
import navbar from "./components/navbar.vue";
//import contactBtns from "./components/contact-btns-fixed.vue";

export default {
  name: "App",
  components: {
    navbar,
    //contactBtns,
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
