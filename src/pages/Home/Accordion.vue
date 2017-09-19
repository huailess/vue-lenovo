<template>
    <mt-swipe :auto="4000" class="accordion">
        <mt-swipe-item style="background:#ccc;"><img src="../../assets/11.jpg"/></mt-swipe-item>
        <mt-swipe-item style="background:#ccc;"><img src="../../assets/22.jpg"/></mt-swipe-item>
        <mt-swipe-item style="background:#ccc;"><img src="../../assets/33.jpg"/></mt-swipe-item>
        <mt-swipe-item style="background:#ccc;"><img src="../../assets/44.jpg"/></mt-swipe-item>
        <mt-swipe-item style="background:#ccc;"><img src="../../assets/55.jpg"/></mt-swipe-item>
        <mt-swipe-item style="background:#ccc;"><img src="../../assets/66.jpg"/></mt-swipe-item>
    </mt-swipe>
</template>

<script>




    export default {
        name:"accordion"
    }



</script>

<style>
    .accordion{
        height:1.8rem;
    }
    img{
        width:100%;
        height:1.8rem;
        background-size:80px 60px;
    }
</style>