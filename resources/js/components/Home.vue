<template>
    <div class="container-fluid">
        <nav-bar/>
        <b-nav-form>
            <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
            <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
        </b-nav-form>
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

</style>
