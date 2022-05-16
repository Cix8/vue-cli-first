<template>
  <div id="app">
    <MyTitle />
    <MyJumbo />
  </div>
</template>

<script>
import MyTitle from "./components/MyTitle.vue";
import MyJumbo from "./components/MyJumbo.vue";

export default {
  name: "App",
  components: {
    MyTitle,
    MyJumbo,
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#app {
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
