<template>
    <div>
        <div class="upcomingEvents_container">
            <div class="upcoming_event">
                <h4>The Gauntlet #33</h4>
                <h5>Rocket League</h5>
                <p>February 5th, 2019 8:00 PM EST </p>
                <div><a href="https://smash.gg" class="event_cta">Register Today!</a></div>
            </div>
            <div class="upcoming_event">
                <h4>The Gauntlet #33</h4>
                <h5>Rocket League</h5>
                <p>February 5th, 2019 8:00 PM EST </p>
                <div><a href="https://smash.gg" class="event_cta">Register Today!</a></div>
            </div>
            <div class="upcoming_event">
                <h4>The Gauntlet #33</h4>
                <h5>Rocket League</h5>
                <p>February 5th, 2019 8:00 PM EST </p>
                <div><a href="https://smash.gg" class="event_cta">Register Today!</a></div>
            </div>
            <div class="upcoming_event">
                <h4>The Gauntlet #33</h4>
                <h5>Rocket League</h5>
                <p>February 5th, 2019 8:00 PM EST </p>
                <div><a href="https://smash.gg" class="event_cta">Register Today!</a></div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'UpcomingEvents'
}
</script>

<style >
h4, h5, p{
    color: black;
}

.upcomingEvents_container{
    height:175px;
    width: 75%;
    border: 2px solid #fff;
    border-radius: 15px;
    right: 5%;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
}

.upcoming_event{
    text-align: center;
    background-color: #fff;
    border-radius: 15px;
}

.event_cta{
    padding: 10px 15px;
    background: #EEC22E;
    border-radius: 15px;
    font-weight: bolder;
    color: #202932;
}

.event_cta:hover{
    background: #EC1C24;
}
</style>