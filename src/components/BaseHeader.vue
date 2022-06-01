<template>
  <header>
    <div class="header__left">
      <img src="../assets/img/dc-logo.png" alt="logo dc small" />
    </div>
    <div class="header__right">
      <nav>
        <ul>
          <li><a href="#">link</a></li>
          <li><a class="active" href="#">link</a></li>
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
  ul {
    display: flex;
    list-style: none;
  }
  a {
    text-decoration: none;
    color: rgb(91, 93, 111);
    text-transform: uppercase;
    display: inline-block;
    padding: 50px 10px;
    &.active {
      color: #0086fa;
      border-bottom: 4px solid #0086fa;
    }
  }
  img {
    width: 75%;
  }
}
</style>
