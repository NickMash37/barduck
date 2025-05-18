<template>
    <div class="schedule">
        <h2>Расписание трансляций</h2>
        <div class="matches">
            <div class="match">
                <p>Брентфорд - Челси 16:00</p>
                <p>Тоттенхэм - Саутгемптон 18:00</p>
                <p>Арсенал - Астон Вилла 22:00</p>
            </div>
            <div class="match">
                <p>Локомотив - ЦСКА 16:30</p>
                <p>Бавария - Штутгарт 18:00</p>
                <p>Реал - Осасуна 22:30</p>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
    h2 {
        text-transform: uppercase;
        margin: 0 auto;
        cursor: default;
    }
    .schedule {
        display: flex;
        flex-direction: column;
        margin: 0 auto;
        padding: 20px;
        width: 491px;
        border-radius: 10px;
        backdrop-filter: blur(100px);
        .matches {
            display: flex;
            .match {
                cursor: default;
                margin: auto;
                display: flex;
                flex-direction: column;
                flex-wrap: wrap;
                
                p {
                    font-size: 14px;
                }
            }
        }
    }
</style>