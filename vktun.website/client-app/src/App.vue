<template>
    <div id="app">
        <navs />
        <b-container fluid class="text-dark bg-light p-t-20" >
          <index />
        </b-container>
    </div>
</template>
<script>
    import Index from './components/Index.vue'
    import Navs from './components/home/navs/index.vue'

    export default {
        name: 'app',
        components: {
            Index,
            Navs
        }
    }
</script>
<style>

    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        position: relative
    }
    .p-t-10{
        padding-top:10px;
    }
    .p-t-20 {
        padding-top: 20px;
    }
</style>
