<template>

  <div class="container my-5">
      <CadastrarRecado></CadastrarRecado>
      <listar-recados></listar-recados>
  </div>

</template>

<script>
import CadastrarRecado from './components/CadastrarRecado.vue';
import ListarRecados from './components/ListarRecados.vue';

export default {
  name: 'App',
  components: {
    CadastrarRecado,
    ListarRecados
}
}
</script>

<style>
  @import url('https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css');

</style>
