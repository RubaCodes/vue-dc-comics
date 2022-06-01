<template>
  <footer>
    <base-footer-top></base-footer-top>
    <base-footer-mid></base-footer-mid>
    <base-footer-bot></base-footer-bot>
  </footer>
</template>

<script>
import BaseFooterBot from './footer/BaseFooterBot.vue';
import BaseFooterMid from './footer/BaseFooterMid.vue';
import BaseFooterTop from './footer/BaseFooterTop.vue';
export default {
  name: 'BaseFooter',
  components: {
    BaseFooterBot,
    BaseFooterMid,
    BaseFooterTop,
  },
};
</script>

<style></style>
