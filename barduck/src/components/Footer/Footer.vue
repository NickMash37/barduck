<template>
    <div class="footer">
        <div class="phone">
            <img src="../../../public/phone.png" alt="">
            <a href="tel:+79016949455">+79016949455</a>
        </div>
        <div class="hours">
            <img src="../../../public/clock.png" alt="">
            <div class="hours-item">
                <p>пн-чт 16:00 - 00:00</p>
                <p>пт 15:00 - 02:00</p>
                <p>сб 13:00 - 02:00</p>
                <p>вс 13:00-00:00</p>
            </div>
        </div>
        <div class="location">
            <img src="../../../public/location.png" alt="">
            <div class="location-item">
                <p>г. Иваново <br> ул. Лежневская 138А</p>
            </div>
        </div>
        <div class="socials">
            <a href="https://vk.com"><img src="../../../public/vk.png" alt="" class="social-item"></a>
            <a href="https://telegram.me"><img src="../../../public/tg.png" alt="" class="social-item"></a>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.footer {
    cursor: default;
    width: 100%;
    padding: 0 50px;
    background-color: #F17A25;
    display: flex;
    justify-content: space-around;
    align-items: center;

    img {
        height: 20px;
    }

    .phone {
        display: flex;
        gap: 15px;

        a {
            text-decoration: none;
        }
    }

    .hours {
        display: flex;
        align-items: center;
        gap: 15px;
    }

    .location {
        display: flex;
        align-items: center;
        gap: 15px;

        &-item {
            display: flex;
            flex-direction: column;
        }
    }

    .socials {
        display: flex;
        justify-content: space-around;
        gap: 20px;

        img {
            height: 30px;
        }
    }
}
</style>