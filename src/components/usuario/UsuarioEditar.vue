<template>
    <div class="usuario-editar">
        <h3>Usuário Editar</h3>
        <p><strong>Código: </strong>{{id}}</p>

        <div id="rodape">
            <h3>Curso Vue</h3>
        </div>
    </div>
</template>

<script>
export default {
props:['id'],

    // data(){
    //     return{
    //         id: this.$route.params.id,
    //     }
    // },

    // watch:{
    //     $route(to, from){
    //         this.id=to.params.id
    //     }
    // },

    methods:{
        irParaInicio(){
            this.$router.push('/usuario')
        }
    }
}
</script>

<style>
    #rodape{
        margin-top: 1000px;
    }
</style>
