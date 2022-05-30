<template>
  <div >
    <HeaderComp />

    <MainComp />

    <FooterComp />
    
  </div>
</template>

<script>
import HeaderComp from '@/components/HeaderComp';
import MainComp from '@/components/MainComp';
import FooterComp from '@/components/FooterComp';

export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    FooterComp
    
  }
}
</script>

<style lang="scss">
@import './assets/style/general'

</style>
