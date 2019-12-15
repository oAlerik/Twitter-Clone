<template>
  <div class="create-tweet">
    <p>Compose a Tweet</p>
    <textarea />
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
  }

  button {
    margin-top: 1em;
  }
}
</style>
