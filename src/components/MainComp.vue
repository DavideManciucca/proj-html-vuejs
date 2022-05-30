<template>
  <div>
    <MainFirst />

    <MainSecond />

    <MainThird />
    <svg class="curved" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 319"><path fill="#e56768" fill-opacity="1" d="M0,32L34.3,58.7C68.6,85,137,139,206,149.3C274.3,160,343,128,411,138.7C480,149,549,203,617,192C685.7,181,754,107,823,85.3C891.4,64,960,96,1029,122.7C1097.1,149,1166,171,1234,170.7C1302.9,171,1371,149,1406,138.7L1440,128L1440,0L1405.7,0C1371.4,0,1303,0,1234,0C1165.7,0,1097,0,1029,0C960,0,891,0,823,0C754.3,0,686,0,617,0C548.6,0,480,0,411,0C342.9,0,274,0,206,0C137.1,0,69,0,34,0L0,0Z"></path></svg>

    <MainFourth />


  </div>
</template>

<script>
import MainFirst from '@/components/MainFirst';
import MainSecond from '@/components/MainSecond';
import MainThird from '@/components/MainThird';
import MainFourth from '@/components/MainFourth'

export default {
  name:'MainComp',
  components:{
    MainFirst,
    MainSecond,
    MainThird,
    MainFourth
  }
}
</script>

<style lang="scss" scoped>
  
</style>