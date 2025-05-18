<template>
    <div class="header">
        <div class="logo">
            <img src="../../../public/logo.png" alt="">
        </div>
        <div class="nav-menu">
            <div class="nav-menu__item">Меню</div>
            <div class="nav-menu__item">Бронирование столов</div>
            <div class="nav-menu__item">Расписание трансляций</div>
            <div class="nav-menu__item">Контакты</div>
        </div>
        <div class="cart">
            <img src="../../../public/cart.png" alt="">
        </div>
    </div>
</template>

<script setup>
</script>

<style lang="scss" scoped>

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 100px;
    width: 1000px;
    margin: 20px auto 0;
    height: 100px;
    background-color: #000;
    color: #fff;
    border-radius: 20px;

    .logo {
        height: 80px;
        display: flex;
    }

    .nav-menu {
        display: flex;
        justify-content: space-around;

        &__item {
            margin: 0 20px;
            cursor: pointer;

            &:hover {
                color: #F17A25;
            }
        }
    }

    .cart {
        background-color: #F17A25;
        border-radius: 50%;
        width: 50px;
        height: 50px;
        cursor: pointer;
    }
}

</style>