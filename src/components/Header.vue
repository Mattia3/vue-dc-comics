<template>
  <header class="header-container">
    <img class="header-logo"  src="../assets/img/dc-logo.png" alt="Logo Dc">

    <ul>
      <small v-for="(item, i) in navbarItems" :key="i"><li ><a :class="i === currentActive ? 'active' : ''" href="#">{{ item.title }} </a></li></small>
    </ul>
  </header>
</template>

<script scoped>
export default {
  name: "Header",
  data(){
    return{
      navbarItems:[
        {
          title: "CHARACTERS",
          href: "#",
        },
        {
          title: "COMICS",
          href: "#",
        },
        {
          title: "MOVIES",
          href: "#",
        },
        {
          title: "TV",
          href: "#",
        },
        {
          title: "GAMES",
          href: "#",
        },
        {
          title: "COLLECTIBLES",
          href: "#",
        },
        {
          title: "VIDEOS",
          href: "#",
        },
        {
          title: "FANS",
          href: "#",
        },
        {
          title: "NEWS",
          href: "#",
        },
        {
          title: "SHOP",
          href: "#",
        },
      ],
      currentActive: 0
    }
  }
}

</script>

<style lang="scss">
@import "../css/variables";

.header-container{
  width: 1330px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  
  .header-logo{
    width: 85px;
  }

  li{
    padding: $padding-y 0;
  }

  ul{
    display: flex;
    list-style-type: none;  
  }
    a{
      text-decoration: none;
      padding: 46px 15px;
      color: #1c1c1c;
      font-weight: bold;
    }
  
  .active{
    border-bottom: 4px solid $color_primary;
    color: $color_primary;
  }

  
}

</style>