<template>
  <div>
    <PrimeiroComponente/>
    <lifeCicle/>
    <NomePessoa/>
  </div>
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import lifeCicle from './components/lifeCicle.vue';
  import NomePessoa from './components/NomePessoa.vue';
  export default {
    name: 'App',
    components: {
      PrimeiroComponente,
      lifeCicle,
      NomePessoa
    }

  }
</script>
