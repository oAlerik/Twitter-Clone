<template>
  <main class="page-container">
    <NavBar />
    <Main />
    <SideBar />
  </main>
</template>

<script>
import Main from "./components/Main.vue";
import NavBar from "./components/NavBar.vue";
import SideBar from "./components/SideBar.vue";

export default {
  components: {
    Main,
    NavBar,
    SideBar
  },
  data() {
    return {};
  }
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css?family=Roboto&display=swap");

* {
  font-family: "Roboto", sans-serif;
}

html,
body,
div {
  padding: 0;
  margin: 0;
  color: #fff;
}

a {
  color: #fff;
  text-decoration: none;
}

.page-container {
  background-color: #ff00ff;
  width: 65%;
  margin: auto;
  display: flex;
}
</style>
