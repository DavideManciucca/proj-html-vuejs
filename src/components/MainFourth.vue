<template>
  <div class="container-fluid d-flex">
    <div class="dm-container">
      <h3>Last Courses</h3>
      <div class="card-container d-flex">
        <div class="box">
          <img src="../assets/img/Decisions-icon.png" alt="">
          <h6>Make Better Decision</h6>
          <div><span class="dm-gray">Teacher:</span><span class="dm-gray-bold">James Colins</span></div>
          <div><span class="dm-gray">Price:</span>$21.00</div>
          <div class="dm-btn btn-yellow">View course</div>
        </div>

        <div class="box">
          <img src="../assets/img/Speaker-icon.png" alt="">
          <h6>How to be a speaker</h6>
          <div><span class="dm-gray">Teacher:</span><span class="dm-gray-bold">James Colins</span></div>
          <div><span class="dm-gray">Price:</span><span class="dm-gray-bold">Free</span></div>
          <div class="dm-btn btn-yellow">View course</div>
        </div>

        <div class="box">
          <img src="../assets/img/Network-icon.png" alt="">
          <h6>Network Introductions</h6>
          <div><span class="dm-gray">Teacher:</span><span class="dm-gray-bold">James Colins</span></div>
          <div><span class="dm-gray">Price:</span><span class="dm-gray-bold">Free</span></div>
          <div class="dm-btn btn-yellow">View course</div>
        </div>

        <div class="box">
          <img src="../assets/img/Brand-icon.png" alt="">
          <h6>Brand Management</h6>
          <div><span class="dm-gray">Teacher:</span><span class="dm-gray-bold">James Colins</span> </div>
          <div><span class="dm-gray">Price:</span><span class="dm-gray-bold">Free</span></div>
          <div class="dm-btn btn-yellow">View course</div>
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
}.dm-container h3{
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
}
.box{
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
}

</style>