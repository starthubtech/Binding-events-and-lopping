<template>
  <div id="app">
    <Header></Header>
    <router-view />
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/header';
import Life from './components/pages/life';
import Footer from './components/footer';
import addBlog from './components/addBlog';

export default {
    components: {
      Header,
      Life,
      Footer,
      addBlog,
    }
  }
</script>

<style>

</style>
