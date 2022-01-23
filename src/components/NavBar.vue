<template>
    <div class="navbar"></div>
</template>

<script>
    export default {
        name: "NavBar",
        props: {
            msg: String,
        },
    };
</script>

<style>
    .navbar {
        position: absolute;
        top: 0;
        height: 30px;
        background-color: #dde7ee;
        width: 100%;
    }
</style>
