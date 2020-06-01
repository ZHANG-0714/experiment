<template>
<!-- 全部课程 -->

 <div>
     <div class="cheng">

         <div class="course">
             <img src="../../../src/assets/01.png" alt="" class="img">
             <div>全部课程</div>
         </div>

     </div>
 </div>
</template>

<script>
 export default {
   name: '',
   props: {
   },
   components: {

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
.cheng{
    margin-left: 200px;
    margin-right: 200px;
}
.course{
    width: 230px;
    height: 60px;
    display: flex;
     align-items: center;
    background-color: #08BF91;
}
.img{
     width: 20px;
    height: 20px;
}

</style>