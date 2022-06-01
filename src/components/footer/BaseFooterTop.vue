<template>
  <div class="footer__top">
    <div class="container">
      <ul>
        <li>
          <div class="card">
            <img
              src="../../assets/img/buy-comics-digital-comics.png"
              alt="buy-digital-comics"
            /><a href="#">link</a>
          </div>
        </li>
        <li>
          <div class="card">
            <img
              src="../../assets/img/buy-comics-merchandise.png"
              alt="buy-comics-merchandise"
            /><a href="#">link</a>
          </div>
        </li>
        <li>
          <div class="card">
            <img
              src="../../assets/img/buy-comics-subscriptions.png"
              alt="buy-comics-subscriptions"
            /><a href="#">link</a>
          </div>
        </li>
        <li>
          <div class="card">
            <img
              src="../../assets/img/buy-comics-shop-locator.png"
              alt="buy-comics-shop-locator"
            /><a href="#">link</a>
          </div>
        </li>
        <li>
          <div class="card">
            <img
              src="../../assets/img/buy-dc-power-visa.svg"
              alt="buy-dc-power-visa"
            /><a href="#">link</a>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BaseFooterTop',
};
</script>

<style lang="scss" scoped>
.footer__top {
  padding: 20px 0;
  background-color: #007cf4;

  .container {
    width: 1200px;
    margin: auto;
  }
  ul {
    display: flex;
    align-items: center;
    justify-content: space-between;
    list-style: none;
  }
  .card {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    a {
      text-decoration: none;
      text-transform: uppercase;
      color: white;
    }
    img {
      width: 30%;
    }
  }
}
</style>
