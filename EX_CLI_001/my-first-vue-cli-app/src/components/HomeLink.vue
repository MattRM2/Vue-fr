<script>
export default {
  name: "HomeLink",
  props: {
    test: String,
  },
};
</script>

<template>
  <div>
    <a href="/">Accueil</a>
    <a :href="test">{{ test }}</a>
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