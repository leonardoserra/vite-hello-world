<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
import background from './components/background.vue';

export default {
  components: {
    AppTitle,
    AppHero,
    background
  }
}
</script>

<template>
  <background />
  <div class="container">
    <AppTitle />
    <AppHero />
  </div>
</template>

<style scoped>
body {
  margin: 0;
}

.container {
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  text-align: center;
  width: 600px;
  margin: 50px auto;
}
</style>
