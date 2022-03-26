// 组件的结构
<template>
    <div class="school">
        <h2>学校姓名: {{name}}</h2>
        <h2>学校地址: {{age}}</h2>
        <button @click="showName">点我提示学生姓名</button>
    </div>
</template>

// 组件交互相关代码
<script>
export default {
    data() {
        return {
            name: 'hebust',
            age: 19,
        }
    },
    methods: {
        showName(){
            alert(this.name);
        }
    },
}
</script>

// 组件的样式
<style>
    .school{
        background-color: aqua;
    }
</style>