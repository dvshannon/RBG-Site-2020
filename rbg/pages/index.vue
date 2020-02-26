<template>
  <div class="home_main_container">
    <b-container class="">
      <b-row class="text-center home_page_sidebar_and_content">
        <b-col  sm="12" md="3" style="color: white;">
          Sidebar
        </b-col>
        <b-col>
          <b-row class="home_page_content_bar">
            <b-col>1 of 3</b-col>
          </b-row>
          <b-row class="home_page_content_bar">
            <b-col>2 of 3</b-col>
          </b-row>
          <b-row class="home_page_content_bar">
            <b-col>3 of 3</b-col>
            <b-col>3 of 3</b-col>
          </b-row>
        </b-col>
        
      </b-row>
    </b-container>
      
  </div>
</template>

<script>
export default {
  components: {

  }
}
</script>

<style scoped>

.row{
  border: 1px solid red;
}

.col{
  border: 1px solid teal;
  color: white;
}

.home_page_sidebar_and_content{
  height: 600px;
}

.home_page_content_bar{
  height: 200px;
}

</style>
