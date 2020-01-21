<template>
  <div>
    <header class="header">
      <ul>
        <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/News">News</nuxt-link>
        </li>
        <!-- <li>
          <a href="https://sectorsixapparel.com/collections/rbg">Shop</a>
        </li> -->
        <li>
          <nuxt-link to="/Teams">Our Teams</nuxt-link>
          <ul>
            <li><nuxt-link to="/Teams/CSGO">CS:GO</nuxt-link></li>
            <li><nuxt-link to="/Teams/RocketLeague">Rocket League</nuxt-link></li>
            <li><nuxt-link to="/Teams/Halo">Halo</nuxt-link></li>
          </ul>  
        </li>
        <li>
          <nuxt-link to="/Events">Events</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/Photos">Photos</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/ContactUs">Contact Us</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/Teams/RocketLeague">Rocket League</nuxt-link>
        </li>
      </ul>
    </header>
  </div>
</template>

<script>
export default {
  name: 'AppHeader'
}
</script>

<style>


</style>


