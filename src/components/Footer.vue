<template>
  <footer>
    <div class="background-image">
      
      <div class="container-footer">
        <div class="list-item">
          <ul>
            <li><h2 class="title-footer">DC Comics</h2></li>
            <li><a href="#">Movie</a></li>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>

          <ul>
            <li><h2 class="title-footer">Shop</h2></li>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>

        <div class="list-column2">
          <ul>
            <li><h2 class="title-footer">DC</h2></li>
             <li><a href="#">Term Of Use</a></li>
            <li><a href="#">Privacy police(New)</a></li>
            <li><a href="#">Ad Choises</a></li>
            <li><a href="#">Adversiting</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>

        <div>
          <ul>
            <li><h2 class="title-footer">SITES</h2></li>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>

        <img class="logo-dc" src="../assets/img/dc-logo-bg.png" alt="">
      </div>
    </div>

    <div class="background-enter">
      <div class="container-enter">
        <div>
          <button class="button-footer">SIGN_UP NOW!</button>
        </div>
        <div class="social-icon">
          <h3 class="title-footer-icon">FOLLOW US</h3>
          <img src="../assets/img/footer-facebook.png" alt="Icona Facebook">
          <img src="../assets/img/footer-periscope.png" alt="Icona Facebook">
          <img src="../assets/img/footer-pinterest.png" alt="Icona Facebook">
          <img src="../assets/img/footer-twitter.png" alt="Icona Facebook">
          <img src="../assets/img/footer-youtube.png" alt="Icona Facebook">
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
}
</script>

<style lang="scss">
@import "../css/variables";
  .background-image{
    background-image: url("../assets/img/footer-bg.jpg");
    background-size: cover;

    .ciao{
        background-image: url("../assets/img/dc-logo-bg.png");
    }

    .container-footer{
      width: 1330px;
      margin: 0 auto;
      display: flex;
      padding: 25px 0px; 
      position: relative;
    }

      .list-item{
        display: flex;
        flex-direction: column;
      }

        .container-footer ul{
          list-style-type: none;
          padding-bottom: 15px;
        }

          .title-footer{
            color: $color_white;
            padding-bottom: 15px;
            text-align: initial;
          }

            .container-footer a{
              text-decoration: none;
              color: gray;
              justify-content: flex-start;
              display: flex;
              padding-bottom: 5px;
            }
      
      .list-column2{
        padding: 0px 60px;
      }

      .logo-dc{
        transform: scale(1.5);
        position: absolute;
        right: 0;
        top: 0px;
        height: 100%;
      }
  }

  .background-enter{
     background-color: #303030;
     z-index: 10;
     position: relative;

    .container-enter{
      display: flex;
      width: 1330px;
      margin: 0 auto;
      justify-content: space-between;
      padding: 40px 0;
      align-items: center;
    }

      .social-icon{
        display: flex;
        align-items: center;
        
        img{
          padding-left: 10px;
        }
      }

        

      .button-footer{
        color: $color_white;
        background-color: $color_black;
        padding: 15px;
        border-color: $color_primary;
        cursor: pointer;
        font-size: 16px;

        &:hover{
          background-color:  $color_primary;
          border-color: $color_white;
          box-shadow: 3px 3px black;
        }
      }

     .title-footer-icon{
        color: $color_primary;
        padding-right: 25px;
      }
      
  }

</style>