<template>
    <h1>Olá Vue!</h1>
    <p> meu nome é {{ nome }}</p>
</template>

<script>
    export default {
        name: 'PrimeiroComponente',
        data() {
            return 
                nome: "Julio"{}
        }
    }
</script>