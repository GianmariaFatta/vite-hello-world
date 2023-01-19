<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  data() {
    return {

    }
  },
  components: {
    AppTitle: AppTitle,
    AppHero: AppHero
  }
}
</script>

<template>
  <div class="container">
    <header>
      <AppTitle />
      <AppHero />
    </header>
  </div>

</template>



<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.container {
  margin: 50px auto;
  max-width: 1000px;
  height: 500px;
  text-align: center;
  border: 2px solid darkred;

}
</style>