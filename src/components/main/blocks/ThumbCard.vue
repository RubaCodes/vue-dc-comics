<template>
  <div class="card">
    <img :src="thumb" :alt="title" />
    <h3>{{ title }}</h3>
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
img {
  width: 100%;
}
h3 {
  padding-top: 0.7rem;
  text-transform: uppercase;
  font-size: 0.8rem;
}
</style>
