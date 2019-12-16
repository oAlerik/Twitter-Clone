<template>
  <div class="create-tweet">
    <h2>Compose a Tweet</h2>
    <textarea placeholder="What's happening?" />
    <button>Tweet</button>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<style lang="scss" scoped>
.create-tweet {
  margin-bottom: 1em;

  textarea {
    width: 100%;
    height: 5em;
    padding: 0.5em;
  }

  button {
    margin-top: 1em;
  }
}
</style>
