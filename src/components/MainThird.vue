<template>
  <div class="container-fluid dm-wrap">
    
    <div class="container dm-cont d-flex">
      <img  class="logo " src="../assets/img/Clock-and-Bell.png" alt="">
      <h3 class="red">University year</h3>

      <div class="d-flex">

      
      <div class="time-text first d-flex">
        <h6>Demo Classes</h6>
        <p>
          In the first week, students try to accomodate with the <br>
          teaching style and choose optional courses
        </p>
      </div>
      <div class="time-text second d-flex">
        <h6>Graduation Day</h6>
        <p>
         On the day of the graduation, all students gather for the <br>
        ceremony and then network and party among others.
         
        </p>
      </div>

      </div>

      <img class="timeline" src="../assets/img/Timeline-Item.png" alt="time line">

       <div class="d-flex">

      
      <div class="time-text third d-flex">
        <h6>Orientation</h6>
        <p>
          First day of the university year, all students ghater for <br>
          the opening ceremony and then network with others.
        </p>
      </div>
      <div class="time-text fourth d-flex">
        <h6>Evaluation</h6>
        <p>
         At the end of a semester, students take a general<br>
         evaluation test for every subject they're learning.
         
        </p>
      </div>

      </div>

      <div><img class="logo" src="../assets/img/upcoming-events-calendar-icon.png" alt="calendar"></div>
      <div><h3>Upcoming Events</h3></div>
      <div class="d-flex event-box">

      <div class="event-card">
        <h5>Coaching Sessions</h5>
       
        <div class="data">
          <img class="data-logo" src="../assets/img/upcoming-events-calendar-icon.png" alt="">
          <span>20 May 21:30 PM</span>
        </div>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsam doloribus asperiores recusandae blanditiis suscipit voluptate debitis ab labore reprehenderit magnam,</p>
        <button class="btn dm-btn ">+ Find more</button>
      </div>

      <div class="event-card">
        <h5>Coaching Sessions</h5>
       
        <div class="data">
          <img class="data-logo" src="../assets/img/upcoming-events-calendar-icon.png" alt="">
          <span>20 May 21:30 PM</span>
        </div>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsam doloribus asperiores recusandae blanditiis suscipit voluptate debitis ab labore reprehenderit magnam,</p>
        <button class="btn dm-btn ">+ Find more</button>
      </div>
      

      <div class="event-card">
        <h5>Coaching Sessions</h5>
       
        <div class="data">
          <img class="data-logo" src="../assets/img/upcoming-events-calendar-icon.png" alt="">
          <span>20 May 21:30 PM</span>
        </div>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsam doloribus asperiores recusandae blanditiis suscipit voluptate debitis ab labore reprehenderit magnam,</p>
        <button class="btn dm-btn ">+ Find more</button>
        <!-- <b-button variant="danger" class="dm-btn dm-button-red">+ Find more</b-button> -->
      </div>
      
      </div>
     
      <b-button variant="warning" class="yellow-btn dm-btn">View All Events</b-button>
    </div>
  
  </div>
</template>

<script>
export default {
  name:"MainThird"
}
</script>

<style lang="scss" scoped>
.dm-wrap{
  background-color: #e56768;
  // margin-top: 200px;
}.dm-cont{
  justify-content: center;
  align-items: center;
  flex-direction: column;
}.dm-cont .logo{
height: 50px;
width: 50px;
margin-bottom: 20px;

}.dm-cont h3{
  font-family: 'Fredoka One', cursive;
  color: #ffffff;
  // background-color: red;
  margin-bottom: 50px;
}.red{
  background-color: red;
}
.timeline{
  height: 130px;
}.time-text{
  flex-direction: column;
  align-items: center;
  text-align: center;
  font-size: 10px;
  color: #ffffff;
}.time-text h6{
  // color: #ffffff;
  font-family: 'Fredoka One', cursive;
}
.first{
  transform: translateX(35px);
}.second{
  transform: translateX(140px);
}.third{
  transform: translateX(-150px);
}.fourth{
  transform: translateX(-30px);
}.event-box{
justify-content: center;
align-items: center;
// height: 150px;
// width: 800px;
text-align: center;
// background-color: red;
}.event-card{
  width: calc(100% / 3);
  border: 1px solid;
  border-radius: 20px;
  padding: 20px;
  margin: 1rem;
  background-color:#ffffff;
}.event-card h5{
  font-family: 'Fredoka One', cursive;
  color: #454545;
}.event-card p{
  color: #8b8b8b;
font-size: 13px;
}.data-logo{
  filter:invert(500%);
  height: 20px;
  width: 20px;
}.data span {
  font-size: 10px;
  color: #8b8b8b;
 
}.btn{
  transform: translateY(40px);
  border: 0;
  font-family: 'Fredoka One', cursive;
  font-size: 13px;
  color: #ffffff;
  background-color: #e56768;
}.yellow-btn{
  background-color: #e9d758;
  margin-top: 40px;
}


 

</style>