<template>
  <div class="container wrapper">
    <Header/>
    <nuxt class="body_container"/>
    <Footer  />
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

  .navbar-nav .nav-link{
    color: white !important;
    font-family: 'Rubik', sans-serif !important;
  }

  .navbar-nav .nav-link:hover {
    color: #f91d27 !important;
    font-family: 'Rubik', sans-serif !important;
  }

  .dropdown-menu{
    background: #292929;
    border: none;
  }

  .dropdown-item{
    color: white !important;
  }

  .dropdown-menu:hover{
    background: #292929;
    border: none;
  }

  .dropdown-item:hover{
    background: #292929;
    color: #f91d27 !important;
  }


  
</style>
