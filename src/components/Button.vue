<template>
    <button><slot></slot></button>
</template>

<script>
    export default {
        name: "Button",
        props:{
            type: {
                type: String,
                 default: 'button'
            }
        }
    }
</script>

<style scoped>

</style>