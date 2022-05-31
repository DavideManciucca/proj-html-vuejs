<template>
  <div class="banner d-flex">
    <h5>Subscrive Now To Our Newsletter!</h5>
    <div class="d-flex">
      <input class="input" type="text" placeholder="Email..."> <div class="test"><span class="  btn-yellow">
        <i class="fa-solid fa-paper-plane"></i>
        </span></div>
    </div>
  </div>
  
</template>

<script>
export default {
  name:"FooterFirst"
}
</script>

<style langh="scss" scoped>
.banner{
  height: 120px;
  margin-top: 50px;
  justify-content: center;
  justify-items: center;
  text-align: center;
  align-items: center;
  background-color: #e56768;
  margin-bottom: 50px;
}.banner h5{
  font-family: 'Fredoka One', cursive;
  color: #ffffffff;
}.input{
  border-radius: 50px;
  border: 0;
  height: 40px;
  margin-left: 60px;
  padding: 5px;
}.btn-yellow{
  background-color: #e9d758;
  border-radius: 50px;
  padding: 10px 15px;  
}.btn-yellow i{
  background-clip: #e9d758;
}
.d-flex{
  align-items: center;
}
.test{
  transform: translateX(-32px);
  cursor: pointer;
  
}

</style>