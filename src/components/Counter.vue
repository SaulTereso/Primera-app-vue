<template>
    <h1>Primer Componente - Counter</h1>
    <h4>Operacion matématica exponencial</h4>
    <p>{{ counter }} <sup>2</sup> = {{ counter * counter }}</p>
</template>

<script>
export default {
    data(){
        return{
            name: 'PrimerComponente',
            counter: 5
        }
    }
}
</script>

