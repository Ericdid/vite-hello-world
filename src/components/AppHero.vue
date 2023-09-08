<script>
export default {
  data() {
    return {
      image: "01",
    };
  },
  methods: {
    getImageUrl(name) {
      return new URL(`../assets/img/${name}.jpg`, import.meta.url).href;
    },
  },
};
</script>

<template>
  <img :src="getImageUrl(image)" alt="" />
</template>

<style></style>
