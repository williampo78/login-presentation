<template>
  <div class="min-h-[100vh] flex flex-col justify-between" id="app">
    <div>
      <Header />
      <Nav />
      <div class="my-[40px]">
        <router-view />
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
import Nav from "@/components/Nav.vue";

export default {
  components: {
    Header,
    Footer,
    Nav,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
