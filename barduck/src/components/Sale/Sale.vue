<template>
    <div class="container sale">
        <p>Акция на пивные напитки</p>
        <p>1 + 1 = 3</p>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.sale {
    border-radius: 10px;
    width: 34%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    backdrop-filter: blur(10px);
    p {
        cursor: default;
        text-transform: uppercase;
        margin: 20px auto 10px;
        font-size: 30px;
    }
}
</style>