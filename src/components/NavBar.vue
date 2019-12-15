<template>
  <ul class="navbar">
    <li v-for="(navlink, index) in navlinks" :key="index">
      <a href="#">{{ navlink }}</a>
    </li>
  </ul>
</template>

<script>
export default {
  data() {
    return {
      navlinks: [
        "Home",
        "Explore",
        "Notifications",
        "Messages",
        "Bookmarks",
        "Lists",
        "Profile",
        "More..."
      ]
    };
  }
};
</script>

<style lang="scss">
.navbar {
  background-color: #002470;
  // position: absolute;
  top: 0;
  padding: 1em;
  margin: 0;
  // width: 25%;
  flex-grow: 2.5;

  list-style: none;

  li {
    font-size: 1.25em;
    margin-bottom: 1em;
  }
}
</style>
