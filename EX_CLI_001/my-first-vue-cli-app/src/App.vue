<script>
import NavLink from "./components/HomeLink.vue";

export default {
  name: "App",
  components: {
    NavLink,
  },
};
</script>

<template>
  <div id="app">
    <nav>
      <NavLink url="/" text="Accueil" />
      <NavLink url="/about" text="About" />
      <NavLink url="/contact" text="Contact" />
    </nav>
  </div>
</template>