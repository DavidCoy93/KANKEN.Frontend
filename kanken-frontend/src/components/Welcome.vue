<template>
    <h2 class="Kankenh2">{{ message }}</h2>
</template>

<script>
export default {
    name: 'Welcome',
    props: {
        message: String
    }
}
</script>

<style scoped>
    .Kankenh2 {
        font-family: fantasy;
        color:seagreen;
        background-color: black;
    }
</style>