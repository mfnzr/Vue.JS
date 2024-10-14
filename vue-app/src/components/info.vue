<template>
    <div>
        <p v-if="esta_trabalhando">Estou trabalhando no momento.</p>
        <p v-else>Estou em busca de novas oportunidades!</p>
        <p>E utilizo as seguintes tecnologias:</p>
        <ul>
            <li>JavaScript</li>
            <li>PHP</li>
            <li>Python</li>
        </ul>
        <p v-if="4 > 2">testando</p>
    </div>
</template>

<script>
export default {
    name: 'Info',
    data() {
        return {
            esta_trabalhando: true
        }
    }
}
</script>