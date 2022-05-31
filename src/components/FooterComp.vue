<template>
  <div>
    <FooterFirst />

    <FooterSecond />

    <FooterThird 
    :sxListComp="this.sxListComp"
    :dxListComp="this.dxListComp"
    :btnCat="this.btnCat"
    />

  </div>
</template>

<script>
import FooterFirst from '@/components/FooterFirst';
import FooterSecond from '@/components/FooterSecond';
import FooterThird from '@/components/FooterThird'



export default {
  name:"FooterComp",
  components:{
    FooterFirst,
    FooterSecond,
    FooterThird,
  },
  data(){
    return{
      sxListComp:[
        {
          text:"Request a website"
        },
        {
          text:"Browse Themes"
        },
        {
          text:"Payment options"
        },
        {
          text:"Support System"
        },
        {
          text:"Checkout"
        },
        {
          text:"Purchase Theme"
        }
      ],
      dxListComp:[
        {
          text:"Purchase Theme"
        },
        {
          text:"Our Benefits"
        },
        {
          text:"Our Team"
        },
        {
          text:"Our Services"
        },
        {
          text:"Other Products"
        },
        {
          text:"My Account"
        }
      ],
      btnCat:[
        {
          text:"ECONOMY"
        },
        {
          text:"DESIGN"
        },
        { 
          text:"COACHING"
        },
        {
          text:"BUSINESS"
        },
        {
          text:"MEDICINE"
        },
        { 
          text:"LAW"
        },
        { 
          text:"FITNESS"
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>