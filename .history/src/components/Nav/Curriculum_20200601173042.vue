<template>
<!-- 全部课程 -->

 <div>
     <div class="cheng">

         <div class="course">
             <img src="../../../src/assets/01.png" alt="" class="img">
             <div>全部课程</div>
         </div>

         <div class="whole">
             <div class="route">路径</div>
             <div class="route">训练营</div>
             <div class="route">楼+</div>
             <div class="route">会员</div>
             <div><img src="https://static.shiyanlou.com/frontend/dist/img/02a4001.svg" alt="" class="imgr"></div>
                   
                <div class="comm">
                  <div> 社区 ▼</div>
                    <div class="discuss">
                        <div class="match">讨论</div>
                        <div class="match">教程库</div>
                        <div class="match">直播</div>
                        <div class="match">比赛</div>
                     </div>
                </div>
                   
         </div>

         <div class="with">
             <input type="text" placeholder="搜索 课程/问答" class="search">
             <div class="accord">♥</div>
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
    width: 80%;
    height: 60px;
    background-color: #fff;
    margin: 0 auto;
    display: flex;
    align-items: center;
}
.course{
    width: 230px;
    height: 60px;
    display: flex;
    color: #fff;
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
    align-items: center;
    font-size: 17px;
    background-color: #fff;
}
.route{
    margin-left: 30px;
}
.route:hover{
    color: #08BF91;
    cursor: pointer;
}
.imgr{
    margin-bottom: 20px;
    margin-left: 10px;
}
.search{
    width: 200px;
    margin-left: 250px;
    padding: 5px 5px;
    border-radius: 5px;
    border: 1px solid #9999A5;
    color: #9999A5;
}
.search:hover{
    border: 1px solid #08BF91;
}
.search:focus{                 //:focus 点击输入框边框效果 
    outline: none;           //没有边框
    border: 1px solid #08BF91;
}
.with{
    position: relative;
}

.accord{
    position: absolute;
    margin-left: 440px;
    margin-top: -25px;
}
.discuss{
    position: absolute;
    width: 150px;
    background-color: #fff;
    display: none;
}
.match{
    width: 200px;
    height: 40px;
}
.comm:hover>.discuss{
    display: block;
}
.match:hover{
    background-color: #9999A5;
}


</style>