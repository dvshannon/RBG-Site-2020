<template>
  <div class="container">
    <AppHeader/>
    <nuxt />
  </div>
</template>


<script>
import AppHeader from '../components/Header';
export default {
  components: {
    AppHeader
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
