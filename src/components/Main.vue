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
@import "../css/variables";
  .main-container{
    background-color: #1c1c1c;

    .container-link{
      width: 1330px;
      margin: 0 auto;
      text-align: initial;
      padding: $padding-y 0px;
    }

      .container-link h2 a{
        text-decoration: none;
        color: $color_white;
      }

  }
</style>