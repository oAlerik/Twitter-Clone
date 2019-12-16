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
    color: #fff;
    background-color: #6510be;
    padding: 0.75em 1.5em;
    margin-top: 1em;
    border: 1px solid #000;
    border-radius: 5%;
  }
}
</style>
