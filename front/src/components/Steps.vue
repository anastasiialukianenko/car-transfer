<script setup>

</script>

<template>
    <section id="steps">
    <h2>Як це працює?</h2>

    <ul>
        <li>
            <p class="number text-sky-300 font-bold">1</p>
            <p class="title">Розрахунок вартості</p>
            <p class="desc">Залежить від маршруту та обраної вами послуги</p>
        </li>
        <li>
            <p class="number text-sky-300 font-bold">2</p>
            <p class="title">Заключення договору</p>
            <p class="desc">Буде гарантом виконання обов'язків з обох сторін</p>
        </li>
        <li>
            <p class="number text-sky-300 font-bold">3</p>
            <p class="title">Перегін авто</p>
            <p class="desc">В обумовлений час та місце наш водій доставить ваш автомобіль</p>
        </li>
        <li>
            <p class="number text-sky-300 font-bold">4</p>
            <p class="title">Оплата послуг</p>
            <p class="desc">Умови оплати обговорюються з нашим менеджером</p>
        </li>
    </ul>
</section>
</template>

<style scoped>
section{
    margin-bottom: 68px;
}
h2{
    font-size: 42px;
    font-weight: 600;
    margin-bottom: 32px;
}

ul{
    display: flex;
    flex-direction: column;
    gap: 34px;
}
li{  display: flex;
    flex-direction: column;
    position: relative;
    padding-left: 60px;
    gap: 12px;
    z-index: 2;
}

.number{
    position: absolute;
    font-size: 68px;
    left: 0;
    top: -10px;

}
.title{
    font-size: 28px;
    text-decoration: underline;
    text-decoration-color: skyblue;
    font-weight: 500;
}
.desc{
    font-size: 18px;
    color: grey;
}

@media screen and (min-width: 1024px) {
    ul{
        flex-direction: row;
        flex-wrap: wrap;
    }
    li{
        width: calc((100% - 40px)/2);
    }
}
</style>
