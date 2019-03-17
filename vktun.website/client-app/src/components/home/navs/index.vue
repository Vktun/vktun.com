<template>
    <b-navbar toggleable="md" type="dark" variant="dark" :sticky=true fixed="top">
        <b-navbar-brand href="#">Vktun.com</b-navbar-brand>
        <b-navbar-toggle target="nav_collapse" />
        <b-collapse is-nav id="nav_collapse">
            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto">
                <b-navbar-nav>
                    <b-nav-item href="#">Index</b-nav-item>
                    <b-nav-item href="#">Blog</b-nav-item>
                    <b-nav-item href="#">.net Core</b-nav-item>
                    <b-nav-item href="#">Javascript</b-nav-item>
                    <b-nav-item href="#">Python</b-nav-item>
                    <b-nav-item href="#">M.L</b-nav-item>
                    <b-nav-item href="#">TypeScript</b-nav-item>
                    <b-nav-item href="#">Html5</b-nav-item>
                    <b-nav-item href="#">Vuejs</b-nav-item>
                    <b-nav-item href="#">Vuejs</b-nav-item>
                </b-navbar-nav>

                <b-nav-item-dropdown right>
                    <!-- Using button-content slot -->
                    <template slot="button-content">
                        <em>User</em>
                    </template>
                    <b-dropdown-item href="#">Profile</b-dropdown-item>
                    <b-dropdown-item href="#">Signout</b-dropdown-item>
                </b-nav-item-dropdown>
            </b-navbar-nav>
        </b-collapse>
    </b-navbar>
</template>

<script>
    export default {

    }
</script>

<style>
</style>
