<template>
  <main class="page-container">
    <Main />
  </main>
</template>

<script>
import Main from "./components/Main.vue";

export default {
  components: {
    Main
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

.page-container {
  background-color: #ff00ff;
  width: 65%;
  margin: auto;
}
</style>
