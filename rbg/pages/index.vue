<template>
  <div class="container home_main_container">
      <div class="sidebar_content">
        <Sidebar class="Sidebar" />
      </div>
      
      <div class="main_content">
        <UpcomingEvents class="UpcomingEvents"/>
        <Accomplishments class="Accomplishments" />
        <div class="half_and_half">
          <HalfLight class="HalfLight" />
          <HalfDark class="HalfDark" />
        </div>
        
      </div>
      
  </div>
</template>

<script>
import Sidebar from '../components/Sidebar';
import UpcomingEvents from '../components/UpcomingEvents';
import Accomplishments from '../components/Accomplishments';
import HalfDark from '../components/HalfDark';
import HalfLight from '../components/HalfLight';
export default {
  components: {
    Sidebar,
    UpcomingEvents,
    Accomplishments,
    HalfDark,
    HalfLight
  }
}
</script>

<style >
.main_content{
  display: flex;
  flex-direction: column;
  width: 79%;
}

.home_main_container{
  display: flex;
}

.half_and_half{
  display: flex;
  flex-direction: row;
  width: 100%;
}

.sidebar_content{
  width: 20%;
}

.UpcomingEvents, .Accomplishments, .HalfLight, .HafDark{
  margin-bottom: 10px;
}

.HalfLight, .HalfDark{
  width: 50%;
  display: flex;
  flex-direction: row;
}

</style>
