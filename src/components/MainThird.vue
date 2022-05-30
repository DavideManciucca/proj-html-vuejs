<template>
  <div class="container-fluid dm-wrap">
    
    <div class="container dm-cont d-flex">
      <img  class="logo" src="../assets/img/Clock-and-Bell.png" alt="">
      <h3>University year</h3>

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
}.dm-cont{
  justify-content: center;
  align-items: center;
  flex-direction: column;
}.dm-cont .logo{
height: 50px;
width: 50px;
}.dm-cont h3{
  font-family: 'Fredoka One', cursive;
  color: #ffffff;
  background-color: red;
  margin-bottom: 50px;
}.timeline{
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
}
 

</style>