<script setup>
let nomes = ['Alice', 'Bruna', 'Caio', 'Daniel'];
</script>
<template>
    <h1>Diretiva v-for</h1>
    <ul>
        <li v-for="nome in nomes">{{ nome }}</li>
    </ul>
</template>