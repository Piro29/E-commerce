<template>
    <div>
        <nav-bar/>
        this is home
    </div>
</template>

<script>
    import NavBar from "./navbar"

    export default {
        name: "Home",
        data() {
            return {};
        },
        components: {
            "nav-bar": NavBar,
        }
    }
</script>

<style>
    .container{
        background-color: black;
    }
</style>
