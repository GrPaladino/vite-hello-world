<script>
export default {
  data() {
    return {
      imageName: "class-avatar.jpeg",
    };
  },

  methods: {
    getImagePath(img) {
      return new URL(`../assets/img/${img}`, import.meta.url).href;
    },
  },
};
</script>

<template>
  <div class="card">
    <img :src="getImagePath(imageName)" alt="" />
  </div>
</template>

<style scoped>
.card {
  width: 800px;
  height: 800px;
  margin: 0 auto;
}

img {
  width: 100%;
}
</style>
