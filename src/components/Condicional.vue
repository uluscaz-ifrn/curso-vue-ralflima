<script setup>
import {ref} from 'vue';
const texto = ref('Texto de exemplo')
const exibir = ref (true);
</script>
<template>
    <h1 v-if="exibir">{{ texto }}</h1>
    <button @click="exibir = !exibir">Click</button>
</template>