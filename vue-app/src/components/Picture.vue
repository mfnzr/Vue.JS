<template>
    <img :src="avatar" width="150px" height="150px" :alt="descricao">
</template>

<script>
export default{
    name: 'Picture',
    data(){
        return {
            avatar: "/img/pngegg.png",
            descricao: "Mickey"
        }
    }
}
</script>

