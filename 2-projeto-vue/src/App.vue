<template>

  <div>
    <primeiroComponente/>
    <p>O dado de app é: {{ testando }}</p>
    <lifeCycle/>
    <pessoa/>
  </div>

</template>

<script>
import lifeCycle from './components/lifeCycle.vue'
import pessoa from './components/pessoa.vue'
import primeiroComponente from './components/primeiroComponente.vue'
 
  export default {
    name: 'App',
    components: {
      primeiroComponente,
      lifeCycle,
      pessoa
    },
    
    data() {
      return {
        testando: "Teste"
      }
    }
  }
</script>