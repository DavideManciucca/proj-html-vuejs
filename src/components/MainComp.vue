<template>
  <div>
    <MainFirst />

    <MainSecond />

    <MainThird />


  </div>
</template>

<script>
import MainFirst from '@/components/MainFirst';
import MainSecond from '@/components/MainSecond';
import MainThird from '@/components/MainThird'

export default {
  name:'MainComp',
  components:{
    MainFirst,
    MainSecond,
    MainThird
  }
}
</script>

<style lang="scss" scoped>

</style>