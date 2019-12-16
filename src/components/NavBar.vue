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
  background-color: #6510be;
  top: 0;
  padding: 1em;
  margin: 0;
  flex-grow: 2.5;
  list-style: none;

  li {
    font-size: 1.25em;
    padding: 0.25em;
    margin-bottom: 1em;
    position: relative;

    &::before {
      content: "";
      position: absolute;
      width: 100%;
      transform: scaleX(0);
      height: 2px;
      bottom: 0;
      left: 0;
      background-color: #fff;
      transform-origin: bottom left;
      transition: transform 0.4s ease-out;
    }

    &:hover::before {
      transform: scaleX(1);
      transform-origin: bottom left;
    }
  }
}
</style>
