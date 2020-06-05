<template>
    <nav class="blue darken-1">
        <div class="nav-wrapper">
            <router-link to="/" class="brand-logo left">Tasks</router-link>
            <ul class="right hide-on-med-and-down">
                <router-link
                    tag="li"
                    exact
                    active-class="active"
                    to="/"
                >
                    <a href="#">Create</a>
                </router-link>

                <router-link
                    tag="li"
                    exact
                    active-class="active"
                    to="/list"
                >
                    <a href="#">List</a>
                </router-link>

            </ul>
        </div>
    </nav>
</template>

<script>
    export default  {}
</script>

<style lang="scss" scoped>
    nav {
        padding: 0 25px;
    }
</style>
