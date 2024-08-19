<script setup>

</script>

<template>
    <section id="conditions">
            <div class="back-image">
        </div>
    <h2>Що необхідно від  Вас?</h2>
    <ul>
        <li class="first">
            <h3>Документи</h3>
            <p> Договір на виконання послуги</p>
            <p>Aкт прийому/передачі автомобіля</p>
            <p>Всі розрахунки здійснюються при отриманні машини (відповідно до суми, зазначеної за виконання послуги за договором, а також компенсація витрат на паливо згідно з чеками).</p>
            <p>Автомобіль передається особі яка зазначена у договорі як сторона, що отримує автомобіль. Обов'язково автівку повинен отримувати або передавати власник за технічним паспартом.</p>
        </li>

        <li class="second">
            <h3>Технічній стан авто</h3>
            <p>При отриманні авто робиться огляд і відправляється Вам відео.</p>
            <p>В акті прийому атомобіля вказуються видимі дефекти авто, якщо вони є, також пробіг авто, і речі які знаходяться в машині.</p>
        </li>

        <li class="third">
            <h3>Страхування</h3>
            <p>Страховий поліс України</p>
            <p>Зелена карта</p>
        </li>

        <li class="second">
            <h3>Маршрут та термін</h3>
            <p>Оговорюються з власником перед складанням договору, в якому зазначаеться маршрут перетину прикордонних пунктів кордону та час виконання послуги.</p>
        </li>

    </ul>
</section>
</template>

<style scoped>
section{
    z-index: 1;
    margin-bottom: 68px;
    position: relative;
}

.back-image {
    position: absolute;
    width: 100%;
    right: 0;
    height: 100%;
    background-image: url(../assets/europe.webp);
    background-size: contain;
    background-repeat: no-repeat;
    z-index: -1;
    top: -330px;
}
h2{
    font-size: 42px;
    font-weight: 600;
    margin-bottom: 32px;
    margin-top: 300px;
    z-index: 2;
}

ul{
    display: flex;
    flex-direction: column;
    gap: 34px;
}
li{
    border-radius: 20px;
    padding: 22px;
    color: #1a1817;
    display: flex;
    flex-direction: column;
    gap: 18px;
}
.first{
    background-color: rgba(174, 185, 255, 0.742);
}
.second{
    background-color: #e2e3e6b4;
}
.third{
    background-color: rgba(125, 212, 252, 0.692); 
}
h3{
    font-size: 32px;
    font-weight: 600;
    margin-bottom: 10px;
}
p{
    font-size: 18px;
    position: relative;
    padding-left: 28px;
}
p::before{
    content: '';
    background-image: url('../assets/circle-right.svg');
    background-size: contain;
    background-repeat: no-repeat;
    width: 20px;
    height: 20px;
    left: 0;
    position: absolute;
}

@media screen and (min-width: 1024px) {
    .back-image {
    width: 60%;
    height: 80%;
    top: -325px;
}
}
</style>
