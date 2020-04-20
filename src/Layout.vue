<template>
  <div>
    <el-tabs v-model="activeName" @tab-click="handleClick">
      <el-tab-pane label="Romain" name="romain">
        <Romain/>
      </el-tab-pane>
      <el-tab-pane label="Demo" name="demo">
        <HelloWorld/>
      </el-tab-pane>
    </el-tabs>
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "./components/HelloWorld.vue";
import Romain from "./components/romain.vue";

@Component({
  components: { Romain, HelloWorld }
})
class Layout extends Vue {
  activeName: string = "romain";

  handleClick(tab, event) {
    console.log(tab, event);
  }
}
export default Layout;
</script>

