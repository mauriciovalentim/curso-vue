<script setup>
import { ref } from "vue";
let validacao = ref(0);
</script>

<style>
.ok {
    color: green;
}
.falha {
    color: red;
}
</style>

<template>
    <select v-model="validacao">
        <option :value="true">Verdadeiro</option>
        <option :value="false">Falso</option>
    </select>
    <p :class="validacao ? 'ok' : 'falha'">Utilizando a diretiva class</p>
    <p>{{ validacao }}</p>
</template>
