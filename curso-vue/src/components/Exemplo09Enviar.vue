<script setup>
function validaFormulario(){
    alert('Formulário enviado!')
}
</script>

<template>
    <form @submit="validaFormulario">
        <input type="submit" value="Enviar">
    </form>
</template>