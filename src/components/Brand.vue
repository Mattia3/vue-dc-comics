<template>
  <div class="brand-container">
    <div class="brand">
      <ul>
        <li  v-for="(item, i) in brandIcons" :key="i"><img :src="item.img" alt="item.title"><a href="#">{{ item.title }}</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Brand",
   data(){
    return{
      brandIcons:[
        {
          img:require("../assets/img/buy-comics-digital-comics.png"),
          title: "DIGITAL COMICS",
          href: "#",
        },
          {
          img:require( "../assets/img/buy-comics-merchandise.png"),
          title: "DC MERCHANDISE",
          href: "#",
        },
          {
          img:require("../assets/img/buy-comics-subscriptions.png"),
          title: "SUBSCRIPTION",
          href: "#",
        },
          {
          img:require("../assets/img/buy-comics-shop-locator.png"),
          title: "COMIC SHOP LOCATOR",
          href: "#",
        },
          {
          img:require("../assets/img/buy-dc-power-visa.svg"),
          title: "DIGITAL COMICS",
          href: "#",
        },
      ],
      
    }
}}

</script>

<style lang="scss">
@import "../css/variables";
  .brand-container{
    background-color: $color_primary;
    z-index: 10;
    position: relative;
    .brand{
      width: 1330px;
      margin: 0 auto;
    }

      .brand ul{
        display: flex;
        list-style-type: none;
        justify-content: space-around;
        padding: $padding-y 0;
      }

        .brand ul a{
          text-decoration: none;
          padding: 0px 20px;
          color: $color_white;
        }

          .brand img{
            width: 50px;
            vertical-align: middle;
            height: 50px;
            object-fit: contain;
          }

  }

 
</style>