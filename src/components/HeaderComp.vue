<template>
  <div>
    
    <HeaderTopComp 
    :headerNav="this.navComp"
    />
    <HeaderJumbo />
 <div class="curved"><svg  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 319"><path fill="#da5f60e6" fill-opacity="1" d="M0,160L48,154.7C96,149,192,139,288,144C384,149,480,171,576,176C672,181,768,171,864,181.3C960,192,1056,224,1152,213.3C1248,203,1344,149,1392,122.7L1440,96L1440,0L1392,0C1344,0,1248,0,1152,0C1056,0,960,0,864,0C768,0,672,0,576,0C480,0,384,0,288,0C192,0,96,0,48,0L0,0Z"></path></svg></div>
  </div>
</template>

<script>
import HeaderTopComp from '@/components/HeaderTopComp';
import HeaderJumbo from '@/components/HeaderJumbo';

export default {
  name:'HeaderComp',
  components:{
    HeaderTopComp,
    HeaderJumbo
    
  },
  data(){
    return{
      navComp:[
        {
          text:"Home",
          href:"#"
        }, 
        {
          text:"Courses",
          href:"#"
        },
        {
          text:"About Us",
          href:"#"
        },
        {
          text:"News",
          href:"#"
        },
        {
          text:"Pages",
          href:"#"
        },
        {
          text:"Contact",
          href:"#"
        },
        {
          text:"Purchase",
          href:"#"
        } 
      ]
    }
  }


}
</script>

<style lang="scss" scoped>

.curved svg {
  margin-bottom: -100px;
}

</style>