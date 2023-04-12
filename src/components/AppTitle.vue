<script>
export default {
    name: 'AppTitle',
    data(){
        return {
            title: "La mia prima app con Vite! (Ci proviamo)"
        }
    }
}
</script>


<template>
    <h1>{{title}}</h1>
</template>


<style>
h1 {
    color: red;
    text-align: center;
    /* margin: 60px 0; */
}
</style>