<script setup>
function mensagem() {
    alert('trabalhando com eventos de clique!')
}
</script>

<template>
    <button @click="mensagem">Clique aqui</button>
</template>