<template>
  <header>
    <div class="header__left">
      <img src="../assets/img/dc-logo.png" alt="logo dc small" />
    </div>
    <div class="header__right">
      <nav>
        <ul>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'BaseHeader',
};
</script>

<style lang="scss" scoped>
header {
  //plain css senza import, i file sass li faro' dopo
  width: 1200px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 0;
  ul {
    display: flex;
    list-style: none;
  }
  a {
    text-decoration: none;
    color: rgb(91, 93, 111);
    text-transform: uppercase;
    display: inline-block;
    padding: 10px;
  }
  img {
    width: 75%;
  }
}
</style>
