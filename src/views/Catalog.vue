<template>
  <div class="container">
    <div class="row">
      <div class="col s12 m3 l3 categories-block">
        <left-menu />
      </div>
      <div class="col s12 m9 l9">
        <h3>Catalog</h3>
        <products-list />
      </div>
    </div>
  </div>
</template>

<script>
import LeftMenu from "../components/LeftMenu";
import ProductsList from "./ProductsList";

export default {
  name: "Catalog",

  components: {
    LeftMenu,
    ProductsList
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
