<template>
  <header class="header-container">
    <img class="header-logo"  src="../assets/img/dc-logo.png" alt="Logo Dc">

    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Home</a></li>
      <li><a href="#">Home</a></li>
      <li><a href="#">Home</a></li>
      <li><a href="#">Home</a></li>
      <li><a href="#">Home</a></li>
      <li><a href="#">Home</a></li>
      <li><a href="#">Home</a></li>
      <li><a href="#">Home</a></li>
      <li><a href="#">Home</a></li>
    </ul>
  </header>
</template>

<script scoped>
export default {
  name: "Header",
}

</script>

<style lang="scss">

.header-container{
  width: 1330px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  
  .header-logo{
    width: 85px;
  }

  ul{
    display: flex;
    list-style-type: none;  
    padding: 50px 0px;
  }
    a{
      text-decoration: none;
      padding: 0px 20px;
      color: black
    }
}

</style>