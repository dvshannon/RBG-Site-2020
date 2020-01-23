<template>
    <div>
        <div class="sidebar_container">
            <h2>Sidebar</h2>
            <div class="sidebar_top"></div>
            <div class="sidebar_tweets"></div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Sidebar'
}
</script>

<style >
.sidebar_container{
    position: absolute;
    height:800px;
    width: 250px;
    left: 5%;
    background-color: #EC1C24;
    border-radius: 15px;
}
</style>