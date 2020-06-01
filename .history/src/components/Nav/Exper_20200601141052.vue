<template>
<!-- 导航栏 -->

 <div>
     
       <Prog></Prog>
       <Curriculum></Curriculum>

     

 </div>

</template>

<script>
import Prog from '../Nav/Prog'
import Curriculum from '../Nav/Curriculum'

 export default {
   name: '',
   props: {
   },
   components: {
     Prog,
     Curriculum

   },
   data () {
     return {

     }
   },
   methods: {

   },
   mounted() {

   },
   watch: {

   },
   computed: {

   }
 }
</script>

<style scoped lang='scss'>
.exper{
    width: 100%;
    background-color: #F9F9F9; 
}

</style>