<template >
    <div id="app" >
        
        <HeaderTop msg="Header text" />
        <Home msg="Hello world!" />
    </div>



</template>

<script>
    import HeaderTop from './components/Header.vue';
    import Home from './components/Home.vue';

    export default {
        name: 'app',
        components: {
            HeaderTop,
            Home
        }
    };
</script>

<style>
</style>
