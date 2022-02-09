<template>
  <div id="app">
    <div class="back">
      <Header />
      <Jumbo />
      <Recipes />
      <Collection />
      <Farm />
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbo from "./components/Jumbo.vue";
import Recipes from "./components/Recipes.vue";
import Collection from "./components/Collection.vue";
import Farm from "./components/Farm.vue";

export default {
  name: "App",
  components: {
    Header,
    Jumbo,
    Recipes,
    Collection,
    Farm,
  },
};
</script>

<style lang="scss">
@import url("https://use.fontawesome.com/releases/v5.7.1/css/all.css");
#app {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.back {
  background-color: #f6f7f1;
}
</style>
