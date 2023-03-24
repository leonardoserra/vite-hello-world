<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <div class="container">
    <AppTitle />
    <AppHero />
  </div>
</template>

<style scoped>
.container {
  width: 600px;
  margin: auto;
}
</style>
