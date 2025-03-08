<script setup>
let nome = 'Lucas'
let idade = 22
let num1 = 4
let num2 = 3 
</script>
<template>
  <p>{{'Olá ' + nome + ' voce tem ' + idade + ' anos.' }}</p>
  <p>{{ num1+num2 }}</p>
</template>