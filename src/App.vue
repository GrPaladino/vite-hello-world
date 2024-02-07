<script>
import JumboHero from "./components/AppHero.vue";
import PageTitle from "./components/AppTitle.vue";

export default {
  data() {
    return {};
  },
  components: {
    PageTitle,
    JumboHero,
  },
};
</script>

<template>
  <PageTitle></PageTitle>
  <JumboHero />
</template>

<style>
@import url("./style.css");
</style>
