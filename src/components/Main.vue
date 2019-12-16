<template>
  <section class="main-container">
    <div class="sub-container">
      <NewTweet />
      <TweetList />
    </div>
  </section>
</template>

<script>
import NewTweet from "./NewTweet.vue";
import TweetList from "./TweetList.vue";

export default {
  components: {
    NewTweet,
    TweetList
  },
  data() {
    return {};
  }
};
</script>

<style lang="scss" scoped>
.main-container {
  background-color: #7e0cf5;
  border-left: 1.5px solid #0000008c;
  flex-grow: 5;
}

.sub-container {
  padding: 1em 2em;
}
</style>
