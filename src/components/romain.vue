<template>
  <div style="margin: 30px;">Romain
    <h1 class="big">La vie d'un chien</h1>
    <h3 class="test">test</h3>
    <p class="medium">
      Pixel se réveille tranquilement d'un paisible sommeil
      quand soudain un énorme bruit éclata
    </p>
    <h2 class="dragon">Le dragon maléfique</h2>
    <p class="moyen">
      le dragon se posait des qustions ou était l'australie.
      <br>surtout que maintenant il était connu dans toutes les villes comment alais t-il s'y prendre la suite vous étonnera.
      <br>le dragon réfléchis pendant longtemps il essaiya de trouver un plan mais rien ne lui venait à l'esprit alors il réfléchit encore et encore
      quand soudain il trouvas une idée il falait que aprendre la langue humainne
      mais comment faire
      <br>il lui faudrai quel qu'un qui le comprene sans le dénoncer au ville alentoure
      il n'avait plus envie de faire de victime.
    </p>
    <p class="moyen2">chapitre</p>
    <h4 class="éléphant">Un éléphant qui se balençait</h4>
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.big {
  color: rgb(49, 117, 161);
  border: 10px dashed;
  padding: 30px;
  background-color: ;
}
.big {
  font-size: 50px;
}
.medium {
  font-size: 20px;
}
.dragon {
  color: rgb(128, 211, 142);
  font-size: 80px;
  border: 5px solid;
  border-radius: 25px;
  background-color: black;
  box-shadow: 8px 8px 12px rgb(49, 46, 46);
}
.moyen {
  font-size: 25px;
}
.moyen2 {
  font-size: 25px;
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-seri;
}
.test {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  color: red;
  box-shadow: 8px 8px 12px rgb(49, 46, 46);
  font-size: 70px;
  padding: 10px;
  font-display: 100px;
}
h2 {
}
.éléphant {
  font-size: 100px;
  border: black solid;
  box-shadow: 8px 8px 12px rgb(49, 46, 46);
  padding: 10px;
}
</style>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({
  name: "Romain"
})
export default class Romain extends Vue {}
</script>

