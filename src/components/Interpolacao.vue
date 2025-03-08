<script setup>
let nome = 'Lucas'
let idade = 22
let num1 = 4
let num2 = 3 
</script>
<template>
  <h1>Interpolação e Concatenação:</h1>
  <p>{{'Olá ' + nome + ' você tem ' + idade + ' anos.' }}</p>
  <h1>Soma dentro do próprio elemento:</h1>
  <p>{{ 'A soma é: ' + (num1+num2) }}</p>
</template>