<template>
  <div class="container wrapper">
    <Header/>
    <nuxt class="body_container"/>
    <!-- <Footer  /> -->
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
    height: 100%;
  }

  .body_container{
    position: absolute;
    top: 150px;
    height: 200vh;
  }

  .wrapper{
    min-height: 100%;
  }
  
</style>
