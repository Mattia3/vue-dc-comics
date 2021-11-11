<template>
  <main class="main-container">
    <div class="container-link">
      <h2><a href="#">Content goes here</a></h2>
    </div>
  </main>
</template>

<script>
export default {
  name: "Main",
}
</script>

<style lang="scss">
  
  .main-container{
    background-color: black;

    .container-link{
      width: 1330px;
      margin: 0 auto;
      text-align: initial;
      padding: 50px 0px;
    }

      .container-link h2 a{
        text-decoration: none;
        color: white;
      }

  }
</style>