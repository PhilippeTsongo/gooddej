<template>
    <div id="app">
        <RestaurantRow/>
    </div>
</template>

<script>

    import RestaurantRow from './components/RestaurantRow.vue';
        export default {
            name: 'App',
            components: {
                RestaurantRow,
        }
    }

</script>

<style>
    @import url('./style/reset.css');
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        padding: 20px;
    }
</style>
