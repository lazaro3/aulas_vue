<template>
    <div class="mensage-container">
        <p>{{ msg }}</p>
    </div>
</template>

<script>
    export default {
        name: 'Mensagem',

        props: {
            msg: String
        }
    }

</script>

<style scoped>
    .mensage-container {
        color: #004085;
        background-color: #cce5ff;
        border-end-end-radius: 5px;
        padding: 10px;
        max-width: 400px;
        margin: 30px auto;
    }

</style>