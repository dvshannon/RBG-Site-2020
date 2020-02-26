<template>
    <b-container class="footer_container">
        <b-row>
            <b-col class="footer_text">Copyright RBG Esports 2020</b-col>
            <b-col>
                <nuxt-link class="footer_text" to="/">Home</nuxt-link>
                <nuxt-link class="footer_text" to="/News">News</nuxt-link>
                <nuxt-link class="footer_text" to="/">Shop</nuxt-link>
            </b-col>
            <b-col>
                <nuxt-link class="footer_text" to="/">Teams</nuxt-link>
                <nuxt-link class="footer_text" to="/News">Events</nuxt-link>
                <nuxt-link class="footer_text" to="/">Photos</nuxt-link>
            </b-col>
            <b-col class="social_media_footer">
                <div>
                    <a href=""><img src="../assets/img/social_media/facebook.png" style="width:20px;height:20px;" alt=""></a>
                </div>

                <div>
                    <a href=""><img src="../assets/img/social_media/twitter.png" style="width:20px;height:20px;" alt=""></a>
                </div>

                <div>
                    <a href=""><img src="../assets/img/social_media/youtube.png" style="width:20px;height:20px;" alt=""></a>
                </div>

                <div>
                    <a href=""><img src="../assets/img/social_media/twitch.png" style="width:20px;height:20px;" alt=""></a>
                </div>

                <div>
                    <a href=""><img src="../assets/img/social_media/discord.png" style="width:20px;height:20px;" alt=""></a>
                </div>
            </b-col>
        </b-row>
    </b-container>
</template>

<script>
export default {
  name: 'OldFooter'
}
</script>

<style>
.footer_container{
    padding: 15px;
    background-color: black;
}

.social_media_footer{
    display: flex;
}

.footer_text{
    color: #AEAEAE;
}
</style>