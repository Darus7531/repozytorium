<template>
  <div id="app">
    <Photo />
    <MyText />
  </div>
</template>

<script>
import MyText from "./components/Text.vue";
import Photo from "./components/Photo.vue";

export default {
  name: "App",
  components: {
    MyText,
    Photo,
  },
};
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
</style>
