<template>
    <div class="root">
        <p id="one">第一段</p>
        <p class="two">第二段</p>
    </div>
</template>

<script>
export default {

}
</script>


<style lang="stylus" scoped>
.root 
    display: flex
    justify-content: center
    color: red
    background-color #aaa
    #one 
        color: blue
    .two
        color: green

   
</style>