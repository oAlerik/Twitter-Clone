<template>
  <section class="main-container">
    <div class="sub-container">
      <NewTweet />
    </div>
  </section>
</template>

<script>
import NewTweet from "./NewTweet.vue";

export default {
  components: {
    NewTweet
  },
  data() {
    return {};
  }
};
</script>

<style lang="scss" scoped>
.main-container {
  width: 50%;
  margin: auto;
  background-color: #0000ff;
}

.sub-container {
  padding: 1em 2em;
}
</style>
