<template>
  <footer>
    <div class="background-image">
      
      <div class="container-footer">
        <div class="list-item">
          <ul>
            <li><h2 class="title-footer">DC Comics</h2></li>
            <li><a href="#">Movie</a></li>
            <li><a href="#">Movie</a></li>
            <li><a href="#">Movie</a></li>
            <li><a href="#">Movie</a></li>
            <li><a href="#">Movie</a></li>
            <li><a href="#">Movie</a></li>
          </ul>

          <ul>
            <li><h2 class="title-footer">Shop</h2></li>
            <li><a href="#">Shop Dc</a></li>
            <li><a href="#">Shop Dc</a></li>
          </ul>
        </div>

        <div class="list-column2">
          <ul>
            <li><h2 class="title-footer">DC</h2></li>
            <li><a href="#">Hello</a></li>
            <li><a href="#">Hello</a></li>
            <li><a href="#">Hello</a></li>
            <li><a href="#">Hello</a></li>
            <li><a href="#">Hello</a></li>
            <li><a href="#">Hello</a></li>
          </ul>
        </div>

        <div class="list-column2">
          <ul>
            <li><h2 class="title-footer">DC</h2></li>
            <li><a href="#">Hello</a></li>
            <li><a href="#">Hello</a></li>
            <li><a href="#">Hello</a></li>
            <li><a href="#">Hello</a></li>
            <li><a href="#">Hello</a></li>
            <li><a href="#">Hello</a></li>
          </ul>
        </div>
      </div>
    </div>

    <div class="background-enter">
      <div class="container-enter">
        <div>
          <button class="button-footer">SIGN_UP NOW!</button>
        </div>
        <div class="social-icon">
          <h2>Follow Us</h2>
          <img src="../assets/img/footer-facebook.png" alt="Icona Facebook">
          <img src="../assets/img/footer-facebook.png" alt="Icona Facebook">
          <img src="../assets/img/footer-facebook.png" alt="Icona Facebook">
          <img src="../assets/img/footer-facebook.png" alt="Icona Facebook">
          <img src="../assets/img/footer-facebook.png" alt="Icona Facebook">
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
            color: white;
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
  }

  .background-enter{
     background-color: black;

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
      }

        .social-icon img{
          padding-left: 10px;
        }

      .button-footer{
        color: white;
        background-color: black;
        padding: 15px;
        border-color: blue;
        cursor: pointer;
      }
      
  }

  
  

</style>