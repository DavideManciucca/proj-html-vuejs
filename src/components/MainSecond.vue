<template>
  <div>



    <div class="text">
      <h1>Faculties available at EduPrime</h1>
      <p>
        A single university with a load courses, tailored <br>
        to statisfy any student's needs
      </p>
    </div>
<!-- container delle facoltà -->
    <div class="box-container">

      <div class="box"></div>
      <div class="box active">
        <img src="../assets/img/Gavel-v2.png" alt="Law Faculty">
        <p>Law faculty</p>
      </div>
      <div class="box">
        <img src="../assets/img/Coins-tabs-v2.png" alt="Economy">
        <p>Economy</p>
      </div>
      <div class="box">
        <img src="../assets/img/Medicine-tabs-v2.png" alt="Medicine">
        <p>Medicine</p>
      </div>
      <div class="box">
        <img src="../assets/img/Computer-tabs-v2.png" alt="Computer Science">
        <p>Computer Science</p>
      </div>
      <div class="box">
        <img src="../assets/img/Palette-tabs-v2.png" alt="Graphic Design">
        <p>Graphic Design</p>
      </div>
      <div class="box"></div>

    </div>

<!--/ container delle facoltà -->

    <div class="area-faculty d-flex">
      <div class="img-active">
        <img src="../assets/img/Gavel-Illustration-e1556884768193.png" alt="Law Faculty">
      </div>

      <div class="description">
        <h3>Law Faculty</h3>
        <p>
          Learning from world-learning academics and practitioners, you'll not only recive <br>
          an outstanding grounding in the theory of law, but you will be able to understand <br>
          how those principles are applied in practice through a range of student-led <br>
          activities and competitions.
        </p>
        <b-button variant="danger" class="dm-btn red-button">Read more</b-button>

      </div>

    </div>

  </div>
</template>

<script>
export default {
  name:"MainSecond"
}
</script>

<style langh="scss" scoped>

.text{
  text-align: center;
}.text h1{
  color: #454545;
  font-family: 'Fredoka One', cursive;
}.text p{
  font-size: 13px;
  color: #151515;
}.box-container{
  display: flex;
}.box{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  height: 180px;
  width: calc(100% / 7);
  border: 1px solid #ececee;
}.box img{
  height: 90px;
  margin-top: 15px;
  /* padding-bottom: 10px; */
}.box p{
  font-family: 'Fredoka One', cursive;
  color: #e56768;
  font-size: 13px;
  margin-top: 5px;
}.red-button{
  background-color:#e56768;
  color: #ffffff;
  font-family: 'Fredoka One', cursive;
  font-size: 13px;
  cursor: pointer;
}
.active{
  background-color: #e56768;
}.active p{
  color: #ffffffcc;
}.active img{
  filter: brightness(200%);
}
.area-faculty{
  justify-content: center;
  margin-top: 70px;
  margin-bottom: 70px;
}.img-active img{
  height: 250px;
}.description h3{
  font-family: 'Fredoka One', cursive;
  color: #454545;
  margin-bottom: 40px;
}.description p {
  font-size: 13px;
  color: #8b8b8a;

}

</style>