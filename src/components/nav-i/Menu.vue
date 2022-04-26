<template>
    <a href="#">Menu{{num}}</a>
</template>

<script>
    export default {
        name:'Menu',
        data() {
            return {
                num: 1,
            }
            
        },
    }
</script>

<style scoped>
    a{
    font-size:7mm;
    min-width: 10px;
    max-width: 190px;
    float: left;
    text-decoration: none;
    color: #f2f2f2;
    padding: 14px 60px;
    padding-top: 20px;
    }
</style>

