<template>
  <div class="dm-jumbo container-fluid d-flex">
    <div class="fixed-left">

      <div>tools 1</div>
      <div>tools 2</div>
      <div>tools 3</div>

    </div>
    <div class="box-jumbo">
      <h1 class="text dm-font">Key to your success</h1>
      <p class="text">EduPrime is the most versatile WordPress theme for educational pruposes, <br>
      showcasing universities, courses, secondary schools etc..
      </p>
      
       <b-button variant="warning" class="dm-button-yellow dm-btn dm-font">
         <font-awesome-icon icon="fa-solid fa-magnifying-glass" />
         Search courses
         </b-button> 
       <b-button variant="light" class="dm-btn dm-btn-white dm-font">Apply for university</b-button>
      
      
    </div>
   


  </div>
  
</template>

<script>
export default {
  name:"HeaderJumbo"

}
</script>

<style langh="scss" scoped>
  .dm-jumbo{
    height: 350px;
    background-color: #da5f60e6;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    text-align: center;
    color: white;
    /* background-image: url(../assets/img/theme_slider2_bg-1.jpg); */
    
  }.text{
    margin-bottom: 40px;
  }
  .dm-button-yellow{
  background-color:#e9d758 ;
  color: #ffffff;
  margin-right: 20px;
  font-size: 12px;
  cursor: pointer;
  
}.dm-btn-white{
  background-color: #ffffff;
  color: #e56768;
  font-size: 12px;
  cursor: pointer;
}.fixed-left{
  position: absolute;
  left: 0;
  z-index: 999;
}

@import "~@fortawesome/fontawesome-free/css/all.min.css"
</style>