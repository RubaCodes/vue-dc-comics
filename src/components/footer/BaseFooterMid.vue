<template>
  <div class="footer__mid">
    <div class="container-lg">
      <div class="footer__mid--main">
        <div class="col">
          <h3>dc Comics</h3>
          <ul>
            <li><a href="#">characters</a></li>
            <li><a href="#">comics</a></li>
            <li><a href="#">movies</a></li>
            <li><a href="#">tv</a></li>
            <li><a href="#">games</a></li>
            <li><a href="#">videos</a></li>
            <li><a href="#">news</a></li>
          </ul>
          <h3>shop</h3>
          <ul>
            <li><a href="#">shop DC</a></li>
            <li><a href="#">shop DC collectibles</a></li>
          </ul>
        </div>
        <div class="col">
          <h3>dc</h3>
          <ul>
            <li><a href="#">terms of use</a></li>
            <li><a href="#">privacy policy (New)</a></li>
            <li><a href="#">ad choices</a></li>
            <li><a href="#">advertising</a></li>
            <li><a href="#">jobs</a></li>
            <li><a href="#">subscriptions</a></li>
            <li><a href="#">talent workshop</a></li>
            <li><a href="#">cpsp certificates</a></li>
            <li><a href="#">ratings</a></li>
            <li><a href="#">shop help</a></li>
            <li><a href="#">contact us</a></li>
          </ul>
        </div>
        <div class="col">
          <h3>sites</h3>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD magazine</a></li>
            <li><a href="#">DC kids</a></li>
            <li><a href="#">DC universe</a></li>
            <li><a href="#">DC power visa</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BaseFooterMid',
};
</script>

<style lang="scss" scoped>
.footer__mid {
  background-image: url('../../assets/img/footer-bg.jpg');
  background-position: center;
  background-size: cover;
  .container-lg {
    width: 1200px;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .footer__mid--main {
    flex-grow: 1;
    padding: 50px 0;
    background-image: url('../../assets/img/dc-logo-bg.png');
    background-position: center right;
    background-repeat: no-repeat;
    display: flex;
    gap: 2rem;
    h3 {
      color: white;
      padding: 15px 0;
      text-transform: uppercase;
    }
    ul {
      list-style: none;
      a {
        display: inline-block;
        padding: 5px 0;
        font-size: 0.8rem;
        text-decoration: none;
        color: #949494;
      }
    }
  }
}
</style>
