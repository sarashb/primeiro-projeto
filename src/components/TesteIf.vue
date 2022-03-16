<template>
    <div class="teste-if">
        <h1 v-if="podeVer">Teste</h1>
        <h1 v-else>Teste2</h1>
    </div>
</template>

<script>
export default {
    name: 'TesteIf',
    data() {
        return {
            podeVer: true
        }
    }
}
</script>

<style scoped>

</style>