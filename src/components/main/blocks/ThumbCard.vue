<template>
  <div class="card">
    <img :src="thumb" :alt="title" />
    <h3>title</h3>
  </div>
</template>

<script>
export default {
  name: 'ThumbCard',
  props: {
    title: String,
    thumb: String,
  },
};
</script>

<style lang="scss" scoped>
h3 {
  text-transform: uppercase;
}
</style>
