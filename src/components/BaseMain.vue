<template>
  <main>
    <MainHero></MainHero>
    <MainShopView></MainShopView>
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
}
</style>
