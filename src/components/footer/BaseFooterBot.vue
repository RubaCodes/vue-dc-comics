<template>
  <div class="footer__bot">
    <div class="container">
      <div class="footer__bot--left">
        <a class="btn__primary" href="#">sign-up now!</a>
      </div>
      <div class="footer__bot--right">
        <span>follow us</span>
        <a href="#"
          ><img src="../../assets/img/footer-facebook.png" alt="facebook" />
        </a>
        <a href="#">
          <img src="../../assets/img/footer-twitter.png" alt="twitter" />
        </a>
        <a href="#"
          ><img src="../../assets/img/footer-youtube.png" alt="youtube" />
        </a>
        <a href="#"
          ><img src="../../assets/img/footer-periscope.png" alt="periscope" />
        </a>
        <a href="#">
          <img src="../../assets/img/footer-pinterest.png" alt="pinterest" />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BaseFooterBot',
};
</script>

<style lang="scss" scoped>
.footer__bot {
  background-color: #333333;
  padding: 30px 0;
  .container {
    width: 1200px;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .footer__bot--right {
    display: flex;
    align-items: center;
    gap: 1rem;
    font-weight: bold;
    color: #0078cf;
    text-transform: uppercase;
  }
  .footer__bot--left {
    a {
      color: white;
      padding: 8px 10px;
      border: 2px solid #0078cf;
      text-decoration: none;
      text-transform: uppercase;
      font-weight: bold;
    }
  }
}
</style>
