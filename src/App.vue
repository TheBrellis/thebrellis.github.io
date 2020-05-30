<template>
  <div id="app">
    <Header />
    <Bio />
    <Projects />
    <Contact />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
// import Bio from "./components/Bio.vue";
// import Projects from "./components/Projects.vue";
// import Contact from "./components/Contact.vue";

export default {
  name: "App",
  components: {
    Header
    // Bio,
    // Projects,
    // Contact
  }
};
</script>

<style>
</style>
