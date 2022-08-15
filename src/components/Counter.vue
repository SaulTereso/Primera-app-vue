<template>
    <h1>Primer Componente - Counter</h1>
    <h4>Operacion matématica exponencial</h4>
    <p>{{ counter }} <sup>2</sup> = {{ counter * counter }}</p>
    <p>{{ counter }} <sup>2</sup> = {{ getSquareValue() }}</p>
    <p>{{ counter }} <sup>2</sup> = {{ squareCounter }}</p>
</template>

<script>
export default {
    data(){
        return{
            name: 'PrimerComponente',
            counter: 5
        }
    },
    //Otras formas de hacer la operacion y tener el mismo resultado
    methods:{
        getSquareValue(){
            return this.counter * this.counter
        }
    },
    //Propiedades computadas - Computed Properties
    computed:{
        squareCounter(){
            return this.counter * this.counter
        }
    }
}
</script>

