<template>
    <div>
        <h1>Hej {{ user }}</h1>
       
    </div>
</template>

<script>

    export default {
        name: 'Home',

        data () {
            return {
                user: "Viktor"
            }
        }
    };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
