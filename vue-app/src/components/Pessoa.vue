<template>
<div>
    <h2>Esta é a descrição da pessoa: {{ nome }}</h2>
    <Info />
    <Form />
</div>
</template>

<script>
import Form from './Form.vue';
import Info from './info.vue';

export default {
    name: 'Pessoa',
    components: {
        Info,
        Form
    },
    data() {
        return {
            nome: 'Maria'
        }
    }
}
</script>