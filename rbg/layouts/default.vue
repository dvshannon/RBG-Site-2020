<template>
  <div class="container wrapper">
    <div class="header_body_wrapper">
      <Header class="header_container"/>
      <nuxt class="body_container"/>
    </div>
    
    <Footer class="footer_container" />
  </div>
</template>


<script>
import Header from '../components/Header';
import Footer from '../components/Footer';
import OldFooter from '../components/OldFooter';
export default {
  components: {
    Header,
    Footer,
    OldFooter
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
    /* width: 1080px;
    margin: 0 auto; */
    background-color: #292929;
    height: 100%;
  }

.header_body_wrapper{
max-width: 95%;
    margin: 0 auto;
}


  .body_container{
    position: relative;
  }

  .body_container{
    position: relative;
  }

  h1{
  text-align: center;
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

.footer_container{
  margin-top: 30px;
}
  
</style>
