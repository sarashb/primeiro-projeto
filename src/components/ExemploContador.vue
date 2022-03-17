<template>
    <div class="exemplo-contador">
        <h2>Contador: {{this.contador}}</h2>
        <button @click="diminuirContador">-</button>
        <button @click="aumentarContador">+</button>
    </div>
</template>

<script>
export default {
    name: 'ExemploContador',
    data() {
        return {
            contador: 0
        }
    },
    methods: {
        aumentarContador() {
            this.contador++;
        },
        diminuirContador() {
            this.contador--;
        }
    }
}
</script>