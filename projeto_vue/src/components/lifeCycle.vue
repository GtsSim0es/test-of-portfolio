<template>
<h1>Meu nome é: {{ nome }}</h1>
</template>

<script>

export default {
    name: 'lifeCycle',
    data() {
        return{
            name: 'ainda não sei'
        }
    },
    created() {
        this.nome = 'Gabriel'
    }
}
</script>