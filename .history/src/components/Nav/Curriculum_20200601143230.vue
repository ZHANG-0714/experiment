<template>
<!-- 全部课程 -->

 <div>
     <div class="cheng">

         <div class="course">
             <img src="../../../src/assets/01.png" alt="" class="img">
             <div>全部课程</div>
         </div>

         <div class="whole">
             <div>路径</div>
             <div>训练营</div>
             <div>楼+</div>
             <div>会员</div>
             <div></div>
             <div>社区 ▼</div>

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
    display: flex;
}
.course{
    width: 230px;
    height: 60px;
    display: flex;
    color: #fff;
    font-size: 50px;
     align-items: center;
    background-color: #08BF91;
}
.img{
     width: 20px;
    height: 20px;
    margin-left: 20px;
    margin-right: 5px;
}
.whole{
    display: flex;
    background-color: #fff;
}

</style>