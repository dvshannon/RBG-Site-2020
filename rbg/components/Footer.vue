<template>
  <div>
      <footer>
          <h4>Copyright RBG Esports 2020</h4>
          <div class="footer_links_cotainer">
              <div class="footer_links_left">
                  <ul>
                      <li><a href="">Home</a></li>
                      <li><a href="">News</a></li>
                      <li><a href="">Shop</a></li>
                  </ul>
              </div>
              <div class="footer_links_right">
                  <ul>
                      <li><a href="">Teams</a></li>
                      <li><a href="">Events</a></li>
                      <li><a href="">Photos</a></li>
                  </ul>
              </div>
          </div>
          <div class="footer_social_icons_container">
              <div>
                  <a href=""><img src="../assets/img/social_media/facebook.png" style="width:35px;height:35px;" alt=""></a>
              </div>
              <div>
                  <a href=""><img src="../assets/img/social_media/twitter.png" style="width:35px;height:35px;" alt=""></a>
              </div>
              <div>
                  <a href=""><img src="../assets/img/social_media/youtube.png" style="width:35px;height:35px;" alt=""></a>
              </div>
              <div>
                  <a href=""><img src="../assets/img/social_media/twitch.png" style="width:35px;height:35px;fill:#C0C6CD" alt=""></a>
              </div>
              <div>
                  <a href=""><img src="../assets/img/social_media/discord.png" style="width:35px;height:35px;fill:#C0C6CD" alt=""></a>
              </div>
          </div>
      </footer>
  </div>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style scoped>
footer{
    bottom: 0;
    display: flex; 
    background-color:#000000;
    width: 100%;
    padding-left: 50px;
}

h4{
    align-self: center;
    color: #AEAEAE;
}

.footer_links_cotainer{
    display: flex;
    margin-left: 50px;
}


.footer_links_left{
    padding: 15px;
    border-right: 1px solid #AEAEAE;
}

.footer_links_right{
padding: 15px;
}

.footer_links_left ul{
    align-self: center;
    display: inline-flex;
    list-style: none;
    flex-direction: column;
}

.footer_links_left ul li{
    list-style: none;
    text-decoration: none;
}

.footer_links_right ul{
    align-self: center;
    display: inline-flex;
    list-style: none;
    flex-direction: column;
}

.footer_links_right ul li{
    list-style: none;
    text-decoration: none;
}

ul li a{
    color: #AEAEAE;
    font-weight: 50;
    font-size: 16px;
}

.footer_social_icons_container{
  display: flex;
  align-self: center;
}

.footer_social_icons_container a{
  margin: 0 10px;
}

@media (max-width: 991px){
.footer_links_cotainer{
    display: block;
}

  .footer_social_icons_container{
    display: block;
  }
}


</style>


