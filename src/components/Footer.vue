<template>
  <footer>
    <div id="shop-section">
      <a href="#">
        <img src="../assets/buy-comics-digital-comics.png" alt="buy" />
        <span>DIGITAL COMICS</span>
      </a>

      <a href="#">
        <img src="../assets/buy-comics-merchandise.png" alt="buy" />
        <span>DC MERCHANDISE</span>
      </a>

      <a href="#">
        <img src="../assets/buy-comics-subscriptions.png" alt="buy" />
        <span>SUBSCRIPTION</span>
      </a>

      <a href="#">
        <img src="../assets/buy-comics-shop-locator.png" alt="maps" />
        <span>COMIC SHOP LOCATOR</span>
      </a>

      <a href="#">
        <img src="../assets/buy-dc-power-visa.svg" alt="buy" />
        <span>DC POWER VISA</span>
      </a>
    </div>

    <div id="footer-info">
      <div id="info-container">
        <div>
          <h3>DC COMICS</h3>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <h3>SHOP</h3>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectebles</a></li>
          </ul>
        </div>

        <div>
          <h3>DC</h3>
          <ul>
            <li><a href="#">Terms Of Use</a></li>
            <li><a href="#">Privacy policy(New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">subscriptions</a></li>
            <li><a href="#">Talent Workshop</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Helps</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>

        <div>
          <h3>SITES</h3>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazione</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
      </div>

      <div id="footer-logo"></div>
    </div>

    <div id="contact-section">
      <div>
        <button>SIGN-UP NOW!</button>
      </div>

      <div id="social-container">
        <p>FOLLOW US</p>
        <a href="#"><img src="../assets/footer-facebook.png" alt="social" /></a>
        <a href="#"><img src="../assets/footer-twitter.png" alt="social" /></a>
        <a href="#"><img src="../assets/footer-youtube.png" alt="social" /></a>
        <a href="#">
          <img src="../assets/footer-pinterest.png" alt="social" />
        </a>
        <a href="#">
          <img src="../assets/footer-periscope.png" alt="social" />
        </a>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
};
</script>

<style  lang="scss" scoped>
#shop-section {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #0282f9;
  padding: 20px 10%;

  a {
    display: flex;
    align-items: center;
    font-size: 14px;
    text-decoration: none;
    color: white;

    &:hover {
      transform: scale(1.1);
    }

    img {
      width: 35px;
      margin-right: 10px;
    }
  }
}

#footer-info {
  display: flex;
  justify-content: space-between;
  background-image: url(../assets/footer-bg.jpg);
  background-position: center;
  background-size: cover;
  padding: 0 10%;

  #info-container {
    display: flex;

    div {
      margin-right: 40px;

      h3 {
        color: white;
        padding: 10px 0;
      }

      li {
        list-style: none;
        margin: 5px 0;

        a {
          text-decoration: none;
          font-size: 14px;
          color: #959595;

          &:hover {
            text-decoration: underline;
          }
        }
      }
    }
  }

  #footer-logo {
    height: 300px;
    width: 400px;
    background-image: url(../assets/dc-logo-bg.png);
    background-position: center;
    background-size: cover;
  }
}

#contact-section {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 10%;
  background-color: hsl(0deg 0% 19%);

  button {
    padding: 10px;
    background-color: hsl(0deg 0% 19%);
    border: 2px solid #0282f9;
    color: white;
    font-weight: 600;
  }

  #social-container {
    display: flex;
    align-items: center;
    color: #0282f9;
    font-weight: 600;

    img {
      margin-left: 15px;
    }
  }
}
</style>