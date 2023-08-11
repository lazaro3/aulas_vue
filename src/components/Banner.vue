<template>
    <div class="maim-bunner">
        <h1>Make your burguer</h1>
    </div>
</template>

<script>
    export default {
        name: 'Bunner',
    }


</script>

<style scoped>

.maim-bunner {
    background-image: url('/public/img/burger.jpg');
    background-position: 0 -500px;
    width: 100%;
    background-size: cover;
    height: 800px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

.maim-bunner h1 {
    color: #fff;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
}


</style>