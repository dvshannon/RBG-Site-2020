<template>
  <div>
    <header class="header menu-area">
      <div><img src="~/assets/img/rbg_logo.png" style="height: 150px; width:200px" alt=""></div>
      <ul>
        <li>
          <nuxt-link class="nuxt-link" to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link class="nuxt-link" to="/News">News</nuxt-link>
        </li>
        <!-- <li>
          <a href="https://sectorsixapparel.com/collections/rbg">Shop</a>
        </li> -->
        <li>
          <nuxt-link class="nuxt-link" to="/OurTeams">Our Teams</nuxt-link>
          <ul class="dropdown1">
            <li><nuxt-link class="nuxt-link subnav" to="/Teams/CSGO">CS:GO</nuxt-link></li>
            <li><nuxt-link class="nuxt-link subnav" to="/Teams/RocketLeague">Rocket League</nuxt-link></li>
            <li><nuxt-link class="nuxt-link subnav" to="/Teams/Halo">Halo</nuxt-link></li>
          </ul>  
        </li>
        <li>
          <nuxt-link class="nuxt-link" to="/Events">Events</nuxt-link>
        </li>
        <li>
          <nuxt-link class="nuxt-link" to="/Photos">Photos</nuxt-link>
        </li>
        <li>
          <nuxt-link class="nuxt-link" to="/ContactUs">Contact Us</nuxt-link>
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
.menu-area .nuxt-link{
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  background: #cb3529;
  height: 50px;
  text-transform: uppercase;
}

.menu-area .nuxt-link:hover{
  color: #BD161C;
}

.menu-area ul li{
  position: relative;
  width: 100%;
  text-align: center;
}

.menu-area ul{
  list-style: none;
  display: flex;
}

.menu-area li:hover .dropdown1 > li{
  top: 0;
  display: block;
}

.dropdown1 li{
  display: none;
  position: absolute;
}

.dropdown1{
  position: relative;
  display: flex;
  flex-direction: column;
}

.subnav{
  font-size: 18px;
}



</style>


