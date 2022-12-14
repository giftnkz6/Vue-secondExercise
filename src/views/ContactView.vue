<template>
    <form action="">
        <input type="text" placeholder="Enter your name">
        <input type="text" placeholder="Enter your surname">
        <input type="email" placeholder="Enter your email">
        <button @click="contactClick()">Submit</button>
    </form>
</template>

<script>
    export default{
        name: "ContactView",
    }
</script>

<style scoped>
    form {
        display: grid;
        grid-template-columns: 1fr;
        width: 280px;
        margin: auto;
    }
    form input{
        width: 280px;
        margin-top: 1rem;
    }
    button{
        width: 80px;
        margin: auto;
        margin-top: 1rem;
    }
</style>