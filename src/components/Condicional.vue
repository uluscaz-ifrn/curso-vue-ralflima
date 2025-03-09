<script setup>
import {ref} from 'vue';
const texto = ref('Texto de exemplo')
const exibir = ref (true);
let media = 8
</script>
<template>
    <h1>Condicionais</h1>
    <h1 v-if="exibir">{{ texto }}</h1>
    <button @click="exibir = !exibir">Click</button>
    <p v-if="media >= 7">Aprovado(a)</p>
    <p v-else-if="media >= 5">Em exame</p>
    <p v-else>Reprovado(a)</p>
</template>