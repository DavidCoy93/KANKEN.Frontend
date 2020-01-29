<template>
    <h2 class="GreetingStyle">Hello {{ User }}</h2>
</template>

<script>
export default {
    name: 'Greeting',
    props: {
        User: String
    }
}
</script>

<style scoped>
    .GreetingStyle {
        background-color:chocolate;
        color: black;
        font-weight: bold;
    }
</style>