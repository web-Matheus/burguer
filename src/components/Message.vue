<template>
    <section class="message-container">
        <p>{{msg}}</p>
    </section>
</template>

<script>
export default {
    name:"Message",
    props:{
        msg:String
    }
}
</script>
<style scoped>
    .message-container{
        color: #004085;
        background-color: #cce5ff;
        border: 2px solid #b8daff;
        border-radius: 5px;
        max-width: 400px;
        padding: 10px;
        margin: 30px auto;
    }
</style>