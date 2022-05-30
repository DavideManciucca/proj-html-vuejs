<template>
  <div class="container-fluid d-flex dm-cont ">
    <div class="logo">
      <img src="../assets/img/theme_eduprime_logo.png" alt=""> 
    </div>

    <div>


      <nav class="navbar navbar-expand-lg dm-nav">
  <div class="container-fluid">
    
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        
        
        <li 
        v-for="(element, index) in headerNav" :key="index"
        class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" :href="element.href" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            {{element.text}}
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li><b-button variant="warning" class="dm-button-yellow dm-btn dm-font">VIEW COURSES</b-button></li>
        
      </ul>
      
    </div>
  </div>
</nav>



    </div>

  </div>
</template>

<script>
export default {
 name:'HeaderTopComp',
 props:{
   headerNav:Array
 }
}
</script>

<style lang="scss" scoped>
.dm-cont{
  justify-content: space-between;
  align-items: center;
  padding: 25px;
  background-color: #da5f60e6;
}.logo{
  height: 40px;
  // background-color: brown;
}.logo img{
  height: 100%;
}.dm-nav ul li a{
  color: white;
  
}.dm-button-yellow{
  background-color:#e9d758 ;
  color: white;
  font-size: 12px;
  cursor: pointer;
 
}

</style>