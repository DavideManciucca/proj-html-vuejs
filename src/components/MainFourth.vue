<template>
  <div class="container-fluid d-flex">
    <div class="dm-container">
      <h1>Last Courses</h1>
      <div class="card-container d-flex">
        <div class="box">
          <img src="../assets/img/Decisions-icon.png" alt="">
          <h6>Make Better Decision</h6>
          <div><span class="dm-gray">
            <i class="fa-solid fa-user"></i>
            Teacher:</span><span class="dm-gray-bold">James Colins</span></div>
          <div><span class="dm-gray">
            <i class="fa-solid fa-money-bill"></i>
            Price:</span>$21.00</div>
          <div class="dm-btn btn-yellow">View course</div>
        </div>

        <div class="box">
          <img src="../assets/img/Speaker-icon.png" alt="">
          <h6>How to be a speaker</h6>
          <div><span class="dm-gray">
            <i class="fa-solid fa-user"></i>
            Teacher:</span><span class="dm-gray-bold">James Colins</span></div>
          <div><span class="dm-gray">
            <i class="fa-solid fa-money-bill"></i>
            Price:</span><span class="dm-gray-bold">Free</span></div>
          <div class="dm-btn btn-yellow">View course</div>
        </div>

        <div class="box">
          <img src="../assets/img/Network-icon.png" alt="">
          <h6>Network Introductions</h6>
          <div><span class="dm-gray">
            <i class="fa-solid fa-user"></i>
            Teacher:</span><span class="dm-gray-bold">James Colins</span></div>
          <div><span class="dm-gray">
            <i class="fa-solid fa-money-bill"></i>
            Price:</span><span class="dm-gray-bold">Free</span></div>
          <div class="dm-btn btn-yellow">View course</div>
        </div>

        <div class="box">
          <img src="../assets/img/Brand-icon.png" alt="">
          <h6>Brand Management</h6>
          <div><span class="dm-gray">
            <i class="fa-solid fa-user"></i>
            Teacher:</span><span class="dm-gray-bold">James Colins</span> </div>
          <div><span class="dm-gray">
            <i class="fa-solid fa-money-bill"></i>
            Price:</span><span class="dm-gray-bold">Free</span></div>
          <div class="dm-btn btn-yellow">View course</div>
        </div>
        <!-- fine card -->
      </div>

<!-- prima parte immagine affiancata testo -->
      <div class="dm-cont-second">
        <div>
        <img class="png" src="../assets/img/Exam-icon.png" alt="exam">
        <h1>The most efficient <br>
          examination method
        </h1>
        <p>
          EduPrime has gathered theacher from arount the globe to <br>
          brainstorm in order to facilitate the evaluation of our students. <br>
          Every theacher from our university has an influence on how <br>
          students are evaluated at his/her subject
        </p>

        <b-button variant="danger" class="dm-btn red-btn">Discover the Method</b-button>
        </div>
        <div class="right-bg">
          <img src="../assets/img/Exam-Illustration.png" alt="exam illustration">
        </div>

      </div>
<!-- /prima parte immagine affiancata testo -->


<!-- seconda parte immagine affiancata testo -->
        <div class="dm-cont-third">
          <div>
            <img class="png" src="../assets/img/Exam-icon-1.png" alt="exam icon">
            <h1>Variable fees for <br> International students</h1>
            <p>
              EduPrime has gathered theacher from arount the globe to <br>
              brainstorm in order to facilitate the evaluation of our students. <br>
              Every theacher from our university has an influence on how <br>
              students are evaluated at his/her subject
            </p>
            <b-button variant="danger" class="dm-btn red-btn">List of fees</b-button>
          </div>
          <div class="left-bg">
            <img src="../assets/img/Girl-Illustration.png" alt="">
          </div>

        </div>

      
    </div>
    
  </div>
</template>

<script>
export default {
  name:"MainFourth"
}
</script>

<style lang="scss" scoped>
.dm-container{
  width: 70%;
}.dm-container h1{
  color: #454545;
  font-family: 'Fredoka One', cursive;
  margin-bottom: 50px;
}.d-flex{
  justify-content: center;
}.card-container{
  justify-content: center;
  align-items: center;
}.dm-gray{
  color: #8b8b8b;
  // color: red;
}.dm-gray-bold{
  color: #5c5e6c;
  font-weight: bold;
}.box{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: calc(100% / 4);
  margin: 0.4rem;
  border: 1px solid #ffffffcc;
  background-color: #f7f8fa;
  padding: 20px;
  box-shadow:  5px  5px 5px #dedede,
              -5px -5px 5px #dedede,
               5px -5px 5px #dedede,
              -5px  5px 5px #dedede;

}.box img{
  height: 70px;
}.box div{
  // margin-top: 8px;
  font-size: 11px;
}.box h6{
  color: #454545;
  font-size: 15px;
  font-family: 'Fredoka One', cursive;
}
.btn-yellow{
  background-color: #e9d758;
  color: #ffffff;
  font-family: 'Fredoka One', cursive;
  transform: translateY(40px);
  cursor: pointer;
}.dm-cont-second{
  margin-top: 50px;
  display: flex;
}.png{
  height: 50px;
}.red-btn{
  background-color: #e56768;
  color:#ffffff;
  font-family: 'Fredoka One', cursive;
  font-size: 13px;
  cursor: pointer;

} p{
  color: #151515;
  font-size: 13px;
  margin-bottom: 40px;
}.right-bg{
  height: 400px;
  width: calc(100% / 2);
  
}.right-bg img{
  height: 100%;
}.dm-cont-third{
  display: flex;
  margin-top: 80px;
  flex-direction: row-reverse;
}.left-bg{
  height: 330px;
  width: calc(100% / 2);
  }.left-bg img{
    height: 100%;
    
  }

</style>