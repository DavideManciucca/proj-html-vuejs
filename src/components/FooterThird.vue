o<template>
  <div class="d-flex dm-footer">
    <div class=" dm-bottom">
    <div class="bottom">Purchase Theme</div>
    <div class="bottom">Related Themes</div>
    </div>

     <div class="sx-col">
      <img src="../assets/img/theme_eduprime_logo.png" alt="logo">
      <p>
        Edu Prime is the most versatile WordPress theme for <br>
        educational puposes, showcasing universities, <br>
        courses, secondary school etc.
      </p>
      <div class="icon-wrapper d-flex">
        <div class="icon"><i class="fa-brands fa-facebook-f"></i></div>
        <div class="icon"><i class="fa-brands fa-twitter"></i></div>
        <div class="icon"><i class="fa-brands fa-instagram"></i></div>
      </div>
    </div>

    <!-- colonna centrale -->
    <div class="middle-col d-flex">
      <div class="sx-list">
        <h6>Get EduPrime</h6>
        <ul>
          <li v-for="(item, index) in sxListComp " :key="index"
          >
            {{item.text}}
          </li>
        </ul>
      </div>
      <div class="dx-list">
        <h6>Networking</h6>
        <ul>
          <li v-for="(item, index) in dxListComp" :key="index" >
            {{item.text}}
          </li>
        </ul>
      </div>
    </div>
    <!-- fine colonna centrale -->

    <div class="dx-col ">
      <div class="d-flex wrap-input">
        <input class="input" type="text" placeholder="Search...">
        <div class="src-btn"><i class="fa-solid fa-magnifying-glass"></i></div>
      </div>
      <!-- <div class="d-flex dm-reverse"> -->
        <h7>Search categories</h7>
        <div class="d-flex cat-btn">
          <div v-for="(item, index) in btnCat" :key="index" class="btn-white">{{item.text}}</div>
          
        </div>
        
      <!-- </div> -->
      
    </div>

  </div>
</template>

<script>
export default {
  name:"FooterThird",
  props:{
    sxListComp:Array,
    dxListComp:Array,
    btnCat:Array
  }
}
</script>

<style lang="scss" scoped>
  .dm-footer{
    height: 400px;
    background-color: #e56768;
    
  }.dm-bottom{
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
  }.bottom{
    font-size: 9px;
    background-color: #454545;
    color: #7f7f7f;
    padding: 8px 25px;
    margin: 5px 10px 15px;
  }.sx-col{
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: calc(100% / 3);
  }h6{
    color: #ffffff;
    font-family: 'Fredoka One', cursive;
  }.sx-col img{
    height: 50px;
    width: 240px;
  }.icon{
    margin: 1rem;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50px;
    border: 2px solid #e9d758;
    height: 50px;
    width: 50px;
  }.middle-col{
    width: calc( 100% /4);
    align-items: center;
    // background-color: red;
  }.sx-list{
    display: flex;
    flex-direction: column;
    width: 50%;
    // background-color: green;
  }.dx-list{
    display: flex;
    flex-direction: column;
  }li{
    list-style: none;
    font-size: 10px;
    margin-left: -32px;
    margin-top: 10px;
    cursor: pointer;
    color: #ffffff;
  }li:hover{
    text-decoration: underline;
  }.dx-col{
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 375px;
    
    // background-color: red;
  }.wrap-input{
    align-items: center;
  }.input{
    border-radius: 20px;
    padding: 10px 20px;
    border: none;
  }.src-btn{
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50px;
    transform: translateX(-43px);
    background-color: #e9d758;
    height: 44px;
    width: 44px;
  }
  .dm-reverse{
    justify-content: flex-end;
  }.cat-btn{
    max-width: 250px;
    justify-content: flex-end;
    flex-wrap: wrap;
    
    // background-color: violet;
  }.btn-white{
    border: 1px solid #ffffff;
    color: #ffffff;;
    padding: 5px 15px;
    font-size: 10px;
    margin: 0.3rem;
    border-radius: 15px;
    
  }
</style>