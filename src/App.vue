<template>
  <Header />
  <TopBlock />
  <Food />
  <Drinks />
  <Footer />
</template>

<script setup>
import Header from "./Header.vue";
import TopBlock from "./TopBlock.vue";
import Food from "./Food.vue";
import Drinks from "./Drinks.vue";
import Footer from "./Footer.vue";
</script>

<style>
body {
  margin: 0px;
}
#app {
  font-family: "Montserrat", sans-serif;
}
</style>
