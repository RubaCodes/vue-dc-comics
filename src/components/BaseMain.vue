<template>
  <main>
    <div class="container">
      <h1>to be filled....</h1>
    </div>
  </main>
</template>

<script>
import MainHero from './main/MainHero.vue';
import MainShopView from './main/MainShopView.vue';
export default {
  name: 'BaseMain',
  components: {
    MainHero,
    MainShopView,
  },
};
</script>

<style lang="scss" scoped>
main {
  background-color: #222222;
  color: white;
  padding: 50px 0;
  .container {
    width: 1200px;
    margin: auto;
  }
}
</style>
