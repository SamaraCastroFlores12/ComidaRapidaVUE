<template>

    
    <grid class="a">
        <img v-bind:src="url" v-bind:alt="nombre">
     <h1>{{nombre}}</h1>
     
     <h2>Costo : ${{costo}}</h2>
     <h3></h3>
     <h3>Descripción: {{descripcion}}</h3>

    </grid>
    
</template>

<script>
import Grid from "./Grid.vue";
    export default{
    props: {
        url: {
            String,
        },
        nombre: {
            String,
        },
        descripcion:{
            String,
        },
        costo:{
            String,
        }
    },
    components: { Grid }
};
</script>

<style scoped>
   
    img{
        width: 10rem;
        height: 10rem;
        padding: 0.5rem;
        background-color:snow;
    }
    a{
        text-decoration: none;
        color:snow;
        background:#301675 ;
        padding: 0.3rem;
        border-radius: 5px;
        border:1px solid #f2f2f2

    }
   
</style>