<template>
  <div id="app">
    <Header></Header>
    <Main></Main>
    <Brand></Brand>
    <Footer></Footer>
  </div>
</template>

<script>

import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
import Brand from "./components/Brand.vue"
import Footer from "./components/Footer.vue"

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Brand,
    Footer
  }
}
</script>

<style lang="scss">
@import "css/variables";
@import "css/utilities";

</style>
