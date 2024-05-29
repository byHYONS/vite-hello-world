<script>
export default {
    nome: 'AppTitle',
    data(){
        return{
            title: 'La mia prima app con Vite!'
        }
    }
}

</script>

<template>
    <h1> {{ title }} </h1>
</template>

<style scoped>
h1 {
    font-size: 38px;
    text-align: center;
    
}
</style>