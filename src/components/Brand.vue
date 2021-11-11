<template>
  <div class="brand-container">
    <div class="brand">
      <ul>
        <li><img src="../assets/img/buy-comics-digital-comics.png" alt="Logo Comics Dc"><a href="#"> Digital Comics</a></li>
        <li><img src="../assets/img/buy-comics-digital-comics.png" alt="Logo Comics Dc"><a href="#"> Digital Comics</a></li>
        <li><img src="../assets/img/buy-comics-digital-comics.png" alt="Logo Comics Dc"><a href="#"> Digital Comics</a></li>
        <li><img src="../assets/img/buy-comics-digital-comics.png" alt="Logo Comics Dc"><a href="#"> Digital Comics</a></li>
        <li><img src="../assets/img/buy-comics-digital-comics.png" alt="Logo Comics Dc"><a href="#"> Digital Comics</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Brand",
}
</script>

<style lang="scss">
  .brand-container{
    background-color: lightblue;
    .brand{
      width: 1330px;
      margin: 0 auto;
    }

      .brand ul{
        display: flex;
        list-style-type: none;
        justify-content: space-around;
        padding: 50px 0;
      }

        .brand ul a{
          text-decoration: none;
          padding: 0px 20px;
          color: white
        }

          .brand img{
            width: 50px;
            vertical-align: middle;
          }

  }
</style>