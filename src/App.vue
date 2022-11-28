<template>
  <div id="app">
    <Navbar></Navbar>
    <Breadcrumb></Breadcrumb>
    <Galley></Galley>
    <Slider></Slider>
    <Footer></Footer>
    <Copy></Copy>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Breadcrumb from './components/Breadcrumb.vue';
import Galley from './components/GalleyComp.vue'
import Slider from './components/Slider.vue';
import Footer from './components/Footer.vue';
import Copy from './components/Copyright.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Breadcrumb,
    Galley,
    Slider,
    Footer,
    Copy
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}

#app {
  margin: 0;
}
</style>
