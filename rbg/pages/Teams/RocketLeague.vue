<template>
    <div>
        <h1 class="player_headline">Rocket League</h1>
        <div class="player_container_row">

            <div class="player_card">
                <img class="player_photo" src="http://placehold.jp/325x200.png" alt="">
                <h4 class="player_gamertag">GAMERTAG</h4>
                <h6 class="player_name">FIRST LAST </h6>
                <div class="social_media_container">
                    <a href=""><img src="../../assets/img/social_media/twitter.png" class="social_media_icon" alt=""></a>
                    <a href=""><img src="../../assets/img/social_media/youtube.png" class="social_media_icon" alt=""></a>
                    <a href=""><img src="../../assets/img/social_media/twitch.png" class="social_media_icon" alt=""></a> 
                </div>
            </div>

            <div class="player_card">
                <img class="player_photo" src="http://placehold.jp/325x200.png" alt="">
                <h4 class="player_gamertag">GAMERTAG</h4>
                <h6 class="player_name">FIRST LAST </h6>
                <div class="social_media_container">
                    <a href=""><img src="../../assets/img/social_media/twitter.png" class="social_media_icon" alt=""></a>
                    <a href=""><img src="../../assets/img/social_media/youtube.png" class="social_media_icon" alt=""></a>
                    <a href=""><img src="../../assets/img/social_media/twitch.png" class="social_media_icon" alt=""></a> 
                </div>
            </div>

            <div class="player_card">
                <img class="player_photo" src="http://placehold.jp/325x200.png" alt="">
                <h4 class="player_gamertag">GAMERTAG</h4>
                <h6 class="player_name">FIRST LAST </h6>
                <div class="social_media_container">
                    <a href=""><img src="../../assets/img/social_media/twitter.png" class="social_media_icon" alt=""></a>
                    <a href=""><img src="../../assets/img/social_media/youtube.png" class="social_media_icon" alt=""></a>
                    <a href=""><img src="../../assets/img/social_media/twitch.png" class="social_media_icon" alt=""></a> 
                </div>
            </div>

        </div>
    </div>


</template>

<script>
export default {
    
}
</script>

<style>
.player_container_row {
  max-width: 1200px;
  height: 200px;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.player_card {
  padding: 10px;
  box-sizing: border-box;
  border: 1px solid white;
  min-width:250px;
  min-height: 400px;
  width: 30%;
  text-align: center;
  background-color: #000000;
  margin-bottom: 25px;
}

.player_photo{
  width: 95%;
  height: 200px;
}

h1{
  text-align: center;
}

.player_gamertag, .player_name{
  padding: 10px 0;
}


.social_media_icon{
  height: 25px;
  width: 25px;
}

.social_media_container a{
  padding: 15px;
}

</style>