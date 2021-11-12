<template>
  <main>
    <div class="jumbotron"></div>
    <div class="main-container">
      <div class="container-link">
        <button class="button-current"><h2><a href="#">CURRENT SERIES</a></h2></button>
        <Card></Card>
      </div>
      <div class="container-button-load">
        <button class="button-load">LOAD MORE</button>
      </div>
      
    </div>
  </main>
</template>

<script>

import Card from "@/components/Card.vue"
export default {
  name: "Main",
  components:{
    Card
  }
}
</script>

<style lang="scss">
@import "../css/variables";
  .jumbotron{
    background-image: url("../assets/img/jumbotron.jpg");
    height: 400px;
  }
  .main-container{
    background-color: #1c1c1c;

    .container-link{
      width: 1330px;
      margin: 0 auto;
      text-align: initial;
      padding: $padding-y 0px;
      position: relative;

        a{
        text-decoration: none;
        color: $color_white;
      }

      .button-current{
        color: $color_white;
        background-color: $color_primary;
        padding: 10px 15px;
        border-color: $color_primary;
        position: absolute;
        top: -25px;
        left: -15px;
      }
    }

     .button-load{
        color: $color_white;
        background-color: $color_primary;
        padding: 7px 43px;
        border-color: $color_primary;
        cursor: pointer;
      }

      .container-button-load{
        text-align: center;
        padding-bottom: 20px;
      }
  }
</style>