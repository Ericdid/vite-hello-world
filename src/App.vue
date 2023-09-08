<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";
export default {
  components: { AppTitle, AppHero },
};
</script>

<template>
  <div class="wrapper">
    <AppTitle />
    <div class="import">
      <AppHero />
    </div>
  </div>
</template>

<style>
.wrapper {
  background-color: rgb(64, 64, 78);
}
.import {
  display: flex;
  justify-content: center;
}
</style>
