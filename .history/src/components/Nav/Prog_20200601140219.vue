<template>
<!-- 实验楼 -->
 <div>
     <div class="ramm">
         <div>
             <img src="https://static.shiyanlou.com/frontend/dist/img/9f43b00.svg" alt="" class="imgs">
         </div>
         <div>做实验,学编程</div>
         <div class="edition">
             <div class="do">企业版 </div>|<div class="dos">学校版</div>
         </div>
         <div class="sign">登录</div>
         <div class="register">注册</div>
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
.imgs{
    width: 120px;
    height: 100px;
}
.ramm{
    margin-left: 200px;
    margin-right: 200px;
    display: flex;
    align-items: center;
}
.edition{
     display: flex;
}
.do{
    color: #9999A5;
    margin-left: 600px;
}
.do:hover{
    color: #08BF91;
}
.dos{
    color: #9999A5;
}
.sign{
    color: #08BF91;
    margin-left: 20px;
}
.register{
    color: #9999A5;
    padding: 10px 20px;
    margin-left: 20px;
    background-color: #08BF91;
}

</style>