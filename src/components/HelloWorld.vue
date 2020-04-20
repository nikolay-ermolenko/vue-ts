<template>
  <div>
    <h1>Test</h1>
    <h2>Titre niveau 2</h2>
    <p>Un paragraphe</p>
    <el-button @click="visible = true">Button</el-button>
    <el-dialog :visible.sync="visible" title="Hello world">
      <p>Try Element</p>
    </el-dialog>
    <el-input-number v-model="num" :min="1" :max="10"></el-input-number>
    <el-date-picker v-model="value2" type="datetime" placeholder="Selectionnez date et horaire"></el-date-picker>
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 55px;
  border: 2px solid yellow;
  background-color: rgb(24, 40, 185);
  color: rgb(69, 235, 3);
}

h2 {
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
  font-size: 25px;
}
</style>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({
  name: "HelloWorld"
})
export default class HelloWorld extends Vue {
  visible: Boolean = false;
  num: number = 0;
  value2: Date = null;
}
</script>

