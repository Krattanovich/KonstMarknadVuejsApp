<template >
    <div id="app" >
        
        <Header msg="Header text" />
        <Home msg="Hello world!" />
    </div>



</template>

<script>
    import Header from './components/Header.vue';
    import Home from './components/Home.vue';

    export default {
        name: 'app',
        components: {
            Header,
            Home
        }
    };
</script>

<style>
</style>
