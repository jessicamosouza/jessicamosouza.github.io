<template>
  <Profile msg="Jéssica Souza" />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Profile from "./components/Profile.vue";

export default defineComponent({
  name: "App",
  components: {
    Profile,
  },
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

template {
    height: 100vh;
}
</style>
