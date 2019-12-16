<template>
  <div class="tweet-list">
    <div v-for="(tweet, index) in tweets" :key="index">
      <h1>{{ tweet.username }}</h1>
      <p>{{ tweet.content }}</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      tweets: [
        {
          username: "Donald Trump",
          content: "interior crocodile alligator"
        },
        {
          username: "Tusk",
          content: "TUSK TUSK TUSK"
        },
        {
          username: "Jordan L",
          content: "Shut up and go home"
        }
      ]
    };
  }
};
</script>

<style lang="scss" scoped>
.tweet-list {
}
</style>
