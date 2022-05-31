<template>
  <div>
    <MainFirst />

    <MainSecond />
    <svg class="curved" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 319"><path fill="#e56768" fill-opacity="1" d="M0,96L34.3,90.7C68.6,85,137,75,206,69.3C274.3,64,343,64,411,96C480,128,549,192,617,213.3C685.7,235,754,213,823,181.3C891.4,149,960,107,1029,117.3C1097.1,128,1166,192,1234,208C1302.9,224,1371,192,1406,176L1440,160L1440,320L1405.7,320C1371.4,320,1303,320,1234,320C1165.7,320,1097,320,1029,320C960,320,891,320,823,320C754.3,320,686,320,617,320C548.6,320,480,320,411,320C342.9,320,274,320,206,320C137.1,320,69,320,34,320L0,320Z"></path></svg>
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