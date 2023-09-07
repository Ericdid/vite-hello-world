<script>
import AppHero from "./components/AppHero.vue";
export default {
  data() {
    return {
      AppTitle: "La mia prima app con Vite!",
    };
  },
  components: { AppHero },
};
</script>

<template>
  <div class="wrapper">
    <h1 class="center-align">{{ AppTitle }}</h1>
    <hr />
    <div class="import">
      <AppHero />
    </div>
  </div>
</template>

<style lang="scss">
.wrapper {
  background-color: rgb(64, 64, 78);
  h1 {
    color: rgb(245, 245, 245);
  }
}
.import {
  display: flex;
  justify-content: center;
}
</style>
