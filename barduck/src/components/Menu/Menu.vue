<template>
    <div class="container menubar">
        <div class="menubar-item">
            <img src="../../../public/fri.png" alt="">
            <p>Меню кухни</p>
        </div>
        <div class="menubar-item">
            <img src="../../../public/beer.png" alt="">
            <p>Меню бара</p>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
    .menubar {
        margin: 0 auto 10px;
        padding: 20px 0;
        gap: 20px;
        width: 34%;
        border-radius: 10px;
        display: flex;
        justify-content: center;
        backdrop-filter: blur(100px);
        
        &-item {
            display: flex;
            justify-content: center;
            flex-direction: column;
            text-align: center;
            cursor: pointer;

            img {
                border: 2px solid #000;
            }

            p {
                cursor: pointer;
            }
        }
    }
</style>