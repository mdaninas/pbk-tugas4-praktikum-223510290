<template>
    <br>
    <button @click="ubahTeks">click me</button>
</template>

<script setup>
const emit = defineEmits(['response'])
function ubahTeks() {
    emit('response', 'BESOK BESOK WEB INI DI UPDATE')
}
</script>