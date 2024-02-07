<script>
import Title from "./components/Apptitle.vue";
import Jumbo from "./components/AppHero.vue";

export default {
  data() {
    return {};
  },
  components: {
    Title,
    Jumbo,
  },
};
</script>

<template>
  <Title></Title>
  <Jumbo />
</template>

<style>
@import url("./style.css");
</style>
