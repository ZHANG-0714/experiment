<template>
<!-- 导航栏 -->

 <div class="gation">
     
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
.gation{
    background-color: #F9F9F9; 
}

</style>