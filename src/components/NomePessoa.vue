<template>
    <div>
        <h2>Esta é a descrição da pessoa: {{ nome }}</h2>
        <InfoNovo/>
    </div>
</template>
<script>
import InfoNovo from './InfoNovo'

export default {
    name: 'NomePessoa',
    components: {
        InfoNovo
    },
    data(){
        return {
            nome: 'Andressa'
        }
    }
}
</script>