<template>
    <!--template代表的就是html的内容，相当于<div id="app"标签中的内容-->
    <div>
        <h1>{{content}}</h1>
        请输入内容:<input type="text" v-model="content">
        <el-button type="warning" round>一个按钮</el-button>
    </div>
</template>
<script>
    export default{
        //在.vue文件中定义data必须使用function，原因是每一个页面都保存了自己的数据
        data:function(){
            //return返回数据，将对象通过return返回给vue-cli
            return{
                 content:""
            }
        }
    }
</script>
<style scoped>/*scoped含义：将当前vue文件中css属性的作用*/
    h1
    {
        color:red;
    }
</style>