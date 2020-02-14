<template>
  <div>
    <b-navbar toggleable="lg">
      <div><nuxt-link class="nuxt-link" to="/"><img src="~/assets/img/rbg_logo.png" class="logo" style="height: 125px; width:175px" alt=""></nuxt-link></div>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item class="nav_link" to="/News">News</b-nav-item>
          <b-nav-item class="nav_link" href="https://sectorsixapparel.com/collections/rbg">Shop</b-nav-item>
        </b-navbar-nav>

        <b-navbar-nav>
          <div >
            <b-nav-item-dropdown class="nav_link" id="dropdown-1" text="Our Teams" right>
              <b-dropdown-item class="nav_link" to="/Teams/CSGO">CS:GO</b-dropdown-item>
              <b-dropdown-item class="nav_link" to="/Teams/RocketLeague">Rocket League</b-dropdown-item>
              <b-dropdown-item class="nav_link" to="/Teams/Halo">Halo</b-dropdown-item>
              <b-dropdown-item class="nav_link" to="/Teams/Staff">Staff</b-dropdown-item>
            </b-nav-item-dropdown>
          </div>
          
          <b-navbar-nav>
          <b-nav-item class="nav_link" to="/Events">Events</b-nav-item>
          <b-nav-item class="nav_link" to="/Photos">Photos</b-nav-item>
          <b-nav-item class="nav_link" to="/ContactUs">Contact Us</b-nav-item>
      </b-navbar-nav>

        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style>
.nav_link{
  padding: 0 10px;
  font-size: 25px;
  font-weight: 300;
}


</style>


