<template>
  <div id="app">
    <Layout/>
    <Romain/>
  </div>
</template>
<style>
html,
body {
  height: 100%;
  margin: 0px;
}
#app {
  height: 100%;
}
</style>

<script>
import HelloWorld from "./components/HelloWorld";
import GridTest from "./components/GridTest";
import Romain from "./components/romain";
import Layout from "./Layout";
import "../node_modules/element-theme-chalk/lib/index.css";
import "../node_modules/element-theme-chalk/lib/icon.css";

export default {
  name: "App",
  components: {
    GridTest,
    Romain,
    Layout
  }
};
</script>

<style>
</style>
