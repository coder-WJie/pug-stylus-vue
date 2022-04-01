<!-- 
1.pug写html,怎么给元素添加属性
2.slot怎么写
3.绑定事件的语法
 -->


<template lang="pug">
    div.hello   hello world
        button(@click="clickEvent()" class="btn") 确认

</template>

<script>
export default {
    methods: {
        clickEvent() {
            console.log(`----------click------------`);
        }
    }
}
</script>

<style>
    .hello {
        color: red;
    }
</style>