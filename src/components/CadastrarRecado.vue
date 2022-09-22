<template>

    <div class="input-group mb-3">
        <input type="text" 
        class="form-control" 
        placeholder="digite seu recado" 
        v-model="recado"
        />

        <button class="btn btn-primary" type="button" id="button-addon2">cdastrar</button>
    </div>
    
    <p>caracteres restantes: <b> {{120 - recado.length}} </b></p>
  
</template>

<script>
export default {
    name : 'CadastrarRecado',
    data(){
        return {
            recado : ''
        }
    }

}
</script>

<style>
    @import url('https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css');

</style>