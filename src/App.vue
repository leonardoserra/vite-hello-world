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
  <div class="body">
    <div class="container">
      <AppTitle />
      <AppHero />
    </div>
  </div>
</template>

<style scoped>
.body {
  width: 100%;
  height: 100%;
  background-image: url(../public/img1.jpg);
  background-size: cover;
  background-repeat: no-repeat;
}

.container {
  text-align: center;
  width: 600px;
  margin: auto;
}
</style>
