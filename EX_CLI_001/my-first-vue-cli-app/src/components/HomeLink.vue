<script>
export default {
  name: "NavLink",
  props: ["url", "text"],
};
</script>

<template>
  <div>
    <a :href="url">{{ text }}</a>
  </div>
</template>

<style>
a {
  text-decoration: none;
  margin: 5px;
}
div {
  display: inline-block;
}
</style>