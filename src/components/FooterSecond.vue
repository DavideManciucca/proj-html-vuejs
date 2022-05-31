<template>
<div>
  <div class="d-flex dm-cont">
    <h1>Partners</h1>
    <p>
      Leverage agile framework to provide a robust synopsis for high level <br>
      overviews. Iterative approaches to corporate strategy.
    </p>
    <div class="d-flex  dm-wrap">
      <div class="logo-box">
        <img class="logo" src="../assets/img/partner-1.png" alt="logo">
      </div>  
      <div class="logo-box">
        <img class="logo" src="../assets/img/partner-2.png" alt="logo">
      </div>  
      <div class="logo-box">
        <img class="logo" src="../assets/img/partner-3.png" alt="logo">
      </div>  
      <div class="logo-box">
        <img class="logo" src="../assets/img/partner-4.png" alt="logo">
      </div>  
      <div class="logo-box">
        <img class="logo" src="../assets/img/partner-5.png" alt="logo">
      </div>  
      <div class="logo-box">
        <img class="logo" src="../assets/img/partner-6.png" alt="logo">
      </div>  
      <div class="logo-box">
        <img class="logo" src="../assets/img/partner-7.png" alt="logo">
      </div>  
      <div class="logo-box">
        <img class="logo" src="../assets/img/partner-8.png" alt="logo">
      </div>  
    
    
    
  </div>
  </div>
    <div class="bg d-flex">
      <img src="../assets/img/background-wave3.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name:"FooterSecond",
  
}
</script>

<style lang="scss" scoped>
.dm-cont{
  text-align: center;
   align-items: center;
   flex-direction: column;
}.dm-cont h1{
  font-family: 'Fredoka One', cursive;
  color: #454545;
}.dm-cont p{
  color: #151515;
  font-size: 13px;
}.dm-wrap{
  width: 70%;
}.logo-box{
  max-height: 50px;
  // max-width: 70px;
  margin: 1rem;
}.logo{
  height: 100%;
  width: 100%;
  filter: opacity(0.5);
}.bg{
  height: 200px;
  justify-content: flex-end;  
}.bg img{
  -webkit-filter: opacity(0.1) brightness(20%) ; 
	filter: opacity(0.1) brightness(20%) ;
  
  
  rotate: 180deg;
  height: 200px;
  max-width: 100%;
}
</style>