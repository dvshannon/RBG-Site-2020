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
      </footer>
  </div>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style>
footer{
    position: absolute;
    bottom: 0;
    display: flex; 
    background-color:#000000;
    width: 100%;
    padding-left: 50px;
}

h4{
    align-self: center;
}

.footer_links_cotainer{
    display: flex;
    margin-left: 50px;
}


.footer_links_left{
    padding: 15px;
    border-right: 1px solid white;
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
    color: white;
    font-weight: 50;
    font-size: 16px;
}




</style>


