<template>
    <div id="box">
        <h2>{{msg}}</h2>
        <button @click="add">点击让money+1</button>
        <p>{{money}}</p>
    </div>
    </template>
<script>
    const box = new Vue({
        el:'#box',
        data:{
            money:0,
            msg:"这是vue得第一个页面"
        },
        methods: {
            add(){
                this.monye=this.money+1
            }
        }
    })
</script>