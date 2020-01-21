<template>
  <div class="container">
    <Header/>
    <nuxt />
    <Footer />
  </div>
</template>


<script>
import Header from '../components/Header';
import Footer from '../components/Footer';
export default {
  components: {
    Header,
    Footer
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  
  }

  body{
    background-color: #292929;
  }
</style>
